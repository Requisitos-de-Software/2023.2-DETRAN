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

## 2. Detran

A seguinte tabela contém foi baseada na [tabela de requisitos elicitados](https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/requisitos_elicitados/#2-documentos-elicitados), porém para a priorização foi adicionado uma nova coluna de categoria em nossa tabela 01 para definir a prioridade de cada requisito.

| Número do Requisito | Categoria       | Requisito                                                                                   |
|---------------------|-----------------|----------------------------------------------------------------------------------------------|
| ADD1                | Must (Deve)     | Baixar o aplicativo em sistemas Android (versão 5 ou superior) e iOS.                        |
| ADD2                | Must (Deve)     | Permitir cadastro no Portal de Serviços, exigindo um endereço de e-mail válido.             |
| ADD3                | Must (Deve)     | Oferecer opção de alteração de senha no aplicativo.                                          |
| ADD4                | Should (Deveria)| Disponibilizar variedade de serviços relacionados à CNH e veículos.                            |
| ADD5                | Must (Deve)     | Garantir compatibilidade com Android 5 ou superior.                                           |
| ADD6                | Must (Deve)     | Assegurar compatibilidade com iOS.                                                            |
| ADD7                | Could (Poderia) | Projetar interface fácil de usar para cadastro no Portal de Serviços.                          |
| ADD8                | Could (Poderia) | Criar interface para alteração de senha de forma intuitiva e segura.                            |
| ADD9                | Could (Poderia) | Apresentar opções de serviço de forma clara e acessível aos usuários.                           |
| ADD10               | Should (Deveria)| Garantir desempenho aceitável em dispositivos Android e iOS.                                    |
| ADD11               | Could (Poderia) | Avaliar risco associado à segurança da alteração de senha e envio de e-mails.                  |
| ADD12               | Should (Deveria)| Realizar testes para validação de funcionalidades do aplicativo.                                  |
| ADD13               | Must (Deve)     | Deve ser possível baixar os boletos com os débitos do meu veículo.                              |
| ADD14               | Must (Deve)     | Deve ser possível realizar o pagamento dos boletos com os débitos do meu veículo.               |
| ADD15               | Must (Deve)     | Deve ser possível baixar os documentos do meu veículo.                                         |
| ADD16               | Must (Deve)     | Deve ser possível consultar os dados de veículos a partir do renavam.                            |
| ADD17               | Must (Deve)     | Deve ser possível consultar os dados de veículos a partir da placa.                               |
| ADD18               | Must (Deve)     | Deve ser possível baixar a minha CNH digital.                                                  |
| ADD19               | Must (Deve)     | Deve ser possível realizar a transferência de veículo.                                         |
| ADD20               | Should (Deveria)| O aplicativo deverá guardar as informações de login do usuário.                                   |
| ADD21               | Must (Deve)     | Receber notificações automáticas sobre a proximidade da expiração da carteira de motorista.     |
| ADD22               | Must (Deve)     | Consultar multas associadas ao veículo de forma rápida e precisa.                                 |
| ADD23               | Must (Deve)     | Pagar multas de trânsito online, utilizando diferentes métodos de pagamento.                     |
| ADD24               | Must (Deve)     | Verificar informações do veículo, incluindo licenciamento e impostos, de forma fácil e conveniente.|
| ADD25               | Could (Poderia) | Receber dicas de segurança personalizadas para o veículo, baseadas nas condições de viagem.       |
| ADD26               | Could (Poderia) | Receber notificações em tempo real sobre atualizações nas leis de trânsito e outras informações relevantes. |
| ADD27               | Should (Deveria)| Agendar atendimento presencial no Detran para evitar filas e garantir eficiência no atendimento. |
| ADD28               | Should (Deveria)| Alterar o endereço associado à CNH sem a necessidade de ir pessoalmente a um posto do Detran.      |
| ADD29               | Should (Deveria)| Alterar o endereço associado ao veículo sem a necessidade de ir pessoalmente a um posto do Detran. |
| ADD30               | Could (Poderia) | Solicitar autorização de estacionamento para idoso por meio do aplicativo.                         |
| ADD31               | Should (Deveria)| Consultar a CNH para verificar sua validade, categoria e pontos de penalidade.                     |
| ADD32               | Should (Deveria)| Consultar informações detalhadas sobre veículos, incluindo histórico de proprietários, débitos pendentes e informações do veículo. |
| ADD33               | Should (Deveria)| Emitir o CRLV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) de forma rápida e fácil, sem precisar ir pessoalmente ao Detran. |
| ADD34               | Could (Poderia) | Solicitar a recolocação de placa em caso de perda, roubo ou dano irreparável pelo aplicativo.    |

<p align="center">
Tabela 01 - Requisitos Priorizados <br>
(Fonte: Vitor Borges)
</p>

## Referências
<a id="QT1" href="#anchor_1">[1] Software Requirements 3rd Edition | Karl Wiegers e Joy Beatty - Microsoft Press, 2013. pg. 320-321</a>

## Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0    | 30/09/2023 | Adicionado introdução sobre MoSCoW | Vitor Borges | Pedro Campos |
| 2.0    | 04/10/2023 | Adicionado tabela com requisitos elicitados | Guilherme Nishimura |Vitor Borges |
