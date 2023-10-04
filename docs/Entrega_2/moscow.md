# MoSCOW

# 1. Introdução
A técnica MoSCoW é uma abordagem de priorização usada em projetos de desenvolvimento de software e gerenciamento de requisitos para determinar quais funcionalidades ou tarefas são mais importantes e quais podem ser adiadas ou excluídas. O nome "MoSCoW" é um acrônimo que representa quatro categorias de prioridade<a id="TEC1" href="#QT1">[1]</a>:

* MUST (Deve ter)
Essa categoria inclui os requisitos ou funcionalidades críticas e essenciais para o sucesso do projeto. São itens sem os quais o projeto não pode ser considerado concluído com êxito. Se um item é classificado como "Must-have" e não é implementado, o projeto é considerado um fracasso.

* SHOULD (Deveria ter)
Itens nesta categoria são importantes, mas não vitais para o lançamento inicial do projeto. Eles são desejáveis e contribuem significativamente para a eficácia do produto, mas o projeto ainda pode ser considerado bem-sucedido sem eles. Os "Should-have" são normalmente considerados para implementação logo após os "Must-have".

* COULD (Poderia ter)
Itens nesta categoria são considerados opcionalmente benéficos. Eles são recursos ou requisitos que podem ser adicionados se houver tempo e recursos disponíveis, mas não são prioritários. A inclusão de itens "Could-have" depende de fatores como prazos e orçamento.

* WOULD (Não terá)
Itens nesta categoria são explicitamente descartados do escopo do projeto atual. Isso não significa que esses itens sejam indesejáveis ou inúteis; simplesmente, não serão considerados durante o projeto atual. Eles podem ser abordados em projetos futuros ou em fases posteriores do projeto atual.

## Detran

Com base nessas informações a equipe gerou uma *tabela 1*  contendo essas informações ao requisitos elicitados.

| Número do Requisito | Categoria    | Descrição |
|---------------------|--------------|-----------|
| ADD1                | Must (Deve)  | Baixar o aplicativo em sistemas Android (versão 5 ou superior) e iOS. |
| ADD2                | Must (Deve)  | Permitir cadastro no Portal de Serviços, exigindo um endereço de e-mail válido. |
| ADD3                | Must (Deve)  | Oferecer opção de alteração de senha no aplicativo. |
| ADD4                | Should (Deveria) | Disponibilizar variedade de serviços relacionados à CNH e veículos. |
| ADD5                | Must (Deve)  | Garantir compatibilidade com Android 5 ou superior. |
| ADD6                | Must (Deve)  | Assegurar compatibilidade com iOS. |
| ADD7                | Could (Poderia) | Projetar interface fácil de usar para cadastro no Portal de Serviços. |
| ADD8                | Could (Poderia) | Criar interface para alteração de senha de forma intuitiva e segura. |
| ADD9                | Could (Poderia) | Apresentar opções de serviço de forma clara e acessível aos usuários. |
| ADD10               | Should (Deveria) | Garantir desempenho aceitável em dispositivos Android e iOS. |
| ADD11               | Could (Poderia) | Risco associado à segurança da alteração de senha e envio de e-mails. |
| ADD12               | Should (Deveria) | Realizar testes para validação de funcionalidades do aplicativo. |
| PE01                | Must (Deve)  | Deve ser possível baixar os boletos com os débitos do meu veículo. |
| PE02                | Must (Deve)  | Deve ser possível realizar o pagamento dos boletos com os débitos do meu veículo. |
| PE03                | Must (Deve)  | Deve ser possível baixar os documentos do meu veículo. |
| PE04                | Must (Deve)  | Deve ser possível consultar os dados de veículos a partir do renavam. |
| PE05                | Must (Deve)  | Deve ser possível consultar os dados de veículos a partir da placa. |
| PE06                | Must (Deve)  | Deve ser possível baixar a minha CNH digital. |
| PE07                | Must (Deve)  | Deve ser possível realizar a transferência de veículo. |
| PE08                | Could (Poderia) | O aplicativo deverá guardar as informações de login do usuário. |
| ST01                | Should (Deveria) | Eu, como usuário, gostaria de receber notificações automáticas quando minha carteira de motorista estiver prestes a expirar. |
| ST02                | Should (Deveria) | Eu, como usuário, gostaria de consultar multas associadas ao meu veículo de forma rápida e precisa. |
| ST03                | Should (Deveria) | Eu, como usuário, gostaria de poder pagar multas de trânsito de forma online, com diferentes métodos de pagamento aceitos. |
| ST04                | Should (Deveria) | Eu, como usuário, gostaria de verificar as informações do meu veículo, incluindo licenciamento e impostos, de forma fácil e conveniente. |
| ST05                | Could (Poderia) | Eu, como usuário, gostaria de receber dicas de segurança personalizadas para minha moto ou carro, de acordo com as condições de viagem. |
| ST06                | Could (Poderia) | Eu, como usuário, gostaria de receber notificações em tempo real sobre atualizações nas leis de trânsito e outras informações importantes. |
| ST07                | Should (Deveria) | Eu, como usuário, gostaria de agendar atendimento presencial no Detran para evitar longas filas e garantir um atendimento mais eficiente. |
| ST08                | Should (Deveria) | Eu, como usuário, gostaria de poder alterar o endereço associado à minha CNH sem a necessidade de ir pessoalmente a um posto do Detran. |
| ST09                | Should (Deveria) | Eu, como usuário, gostaria de poder alterar o endereço associado ao meu veículo sem a necessidade de ir pessoalmente a um posto do Detran. |
| ST10                | Could (Poderia) | Eu, como usuário, gostaria de solicitar autorização de estacionamento para idoso por meio do aplicativo. |
| ST11                | Should (Deveria) | Eu, como usuário, gostaria de consultar minha CNH para verificar sua validade, categoria e pontos de penalidade. |
| ST12                | Should (Deveria) | Eu, como usuário, gostaria de consultar informações detalhadas sobre veículos, incluindo histórico de proprietários, débitos pendentes e informações do veículo. |
| ST13                | Should (Deveria) | Eu, como usuário, gostaria de emitir o CRLV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) de forma rápida e fácil, sem precisar ir pessoalmente ao Detran. |
| ST14                | Could (Poderia) | Eu, como usuário, gostaria de solicitar a recolocação de placa em caso de perda, roubo ou dano irreparável pelo aplicativo. |
| ST15                | Could (Poderia) | Eu, como usuário, gostaria de solicitar a segunda via do CRV (DUT) pelo aplicativo em caso de perda ou roubo do documento original. |
| ST16                | Must (Deve)  | Eu, como usuário, desejo utilizar o aplicativo em dispositivos Android e iOS. |
| ST17                | Must (Deve)  | Eu, como usuário, desejo ter a segurança dos meus dados e dos dados do meu veículo. |





## Referências
> <a id="QT1" href="#anchor_1">[1] Software Requirements 3rd Edition | Karl Wiegers e Joy Beatty - Microsoft Press, 2013. pg. 320-321</a>

# Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0    | 30/09/2023 | Adicionado introdução sobre MoSCoW | Vitor Borges | Pedro Campos |
| 2.0    | 04/10/2023 | Adicionado tabela com requisitos elicitados | Guilherme Nishimura |Vitor Borges |
