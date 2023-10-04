# First Thing First

## Introdução


A abordagem "First Things First" em requisitos refere-se a uma estratégia de priorização no processo de desenvolvimento de software e gestão de requisitos. Essa abordagem enfatiza a importância de identificar e abordar primeiro os requisitos mais críticos e essenciais de um projeto, antes de lidar com requisitos menos importantes.




## Detran

A seguir se encontra a *tabela 1*  com a tabela levantada pela equipe para o aplicativo Detran




*tabela 1*
| Funcionalidade                     | Benefício Relativo | Penalidade Relativa | Valor Total | Valor Total % | Custo Relativo | Custo Relativo % | Risco Relativo | Risco Relativo % | Prioridade  | Requisitos                                                                                   |
|------------------------------------|--------------------|----------------------|-------------|---------------|----------------|------------------|----------------|------------------|------------|----------------------------------------------------------------------------------------------|
| CNH digital                        | 9                  | 9                   | 18          | 14.76         | 3              | 6.98             | 2              | 5.13             | 1.636363636 | ADD3, ADD6, ST11                                                                             |
| CRLV digital                       | 8                  | 9                   | 17          | 13.84         | 4              | 9.30             | 4              | 10.26            | 0.860215054 | ADD12, ST13, PE01, PE03, ST12                                                                |
| Vencimento da CNH                  | 6                  | 6                   | 12          | 9.84          | 6              | 13.95            | 5              | 17.95            | 0.705882353 | ADD3, ST11                                                                                   |
| Gerenciamento de infrações e multas | 7                  | 8                   | 15          | 12.3          | 8              | 18.60            | 7              | 20.51            | 0.660377358 | PE04, PE05, ST02, ST03, ST12, ADD4                                                          |
| Indicação de principal condutor    | 5                  | 4                   | 9           | 7.38          | 9              | 20.93            | 9              | 23.08            | 0.238095238 | ADD7                                                                                          |
| Notificação de recall              | 3                  | 2                   | 5           | 4.1           | 4              | 9.30             | 4              | 12.82            | 0.222222222 | ADD11                                                                                        |
| Histórico de emissão da CNH        | 3                  | 3                   | 6           | 4.92          | 9              | 20.93            | 8              | 23.08            | 0.195121951 | ADD12, ST11                                                                                  |
| Segurança de Dados                 | 5                  | 4                   | 9           | 7.38          | 7              | 16.28            | 8              | 23.08            | 0.238095238 | ADD8, ST17                                                                                   |
| Total                              | 46                 | 45                  | 91          | 100           | 48             | 100              | 39             | 100              | 5.420289855 | -                                                                                            |

Fonte:Autores



A *Tabela 2* abaixo indica a legenda dos codigos dos requisitos:

*Tabela 2*

| Número do Requisito | Categoria | Descrição |
|---------------------|-----------|-----------|
| ADD1                | RF        | Baixar o aplicativo em sistemas Android (versão 5 ou superior) e iOS. |
| ADD2                | RF        | Permitir cadastro no Portal de Serviços, exigindo um endereço de e-mail válido. |
| ADD3                | RF        | Oferecer opção de alteração de senha no aplicativo. |
| ADD4                | RF        | Disponibilizar variedade de serviços relacionados à CNH e veículos. |
| ADD5                | RNF       | Garantir compatibilidade com Android 5 ou superior. |
| ADD6                | RNF       | Assegurar compatibilidade com iOS. |
| ADD7                | RI        | Projetar interface fácil de usar para cadastro no Portal de Serviços. |
| ADD8                | RI        | Criar interface para alteração de senha de forma intuitiva e segura. |
| ADD9                | RI        | Apresentar opções de serviço de forma clara e acessível aos usuários. |
| ADD10               | RPR       | Garantir desempenho aceitável em dispositivos Android e iOS. |
| ADD11               | RR        | Risco associado à segurança da alteração de senha e envio de e-mails. |
| ADD12               | RT        | Realizar testes para validação de funcionalidades do aplicativo. |
| PE01                | RF        | Deve ser possível baixar os boletos com os débitos do meu veículo. |
| PE02                | RF        | Deve ser possível realizar o pagamento dos boletos com os débitos do meu veículo. |
| PE03                | RF        | Deve ser possível baixar os documentos do meu veículo. |
| PE04                | RF        | Deve ser possível consultar os dados de veículos a partir do renavam. |
| PE05                | RF        | Deve ser possível consultar os dados de veículos a partir da placa. |
| PE06                | RF        | Deve ser possível baixar a minha CNH digital. |
| PE07                | RF        | Deve ser possível realizar a transferência de veículo. |
| PE08                | RNF       | O aplicativo deverá guardar as informações de login do usuário. |
| ST01                | RF        | Eu, como usuário, gostaria de receber notificações automáticas quando minha carteira de motorista estiver prestes a expirar. |
| ST02                | RF        | Eu, como usuário, gostaria de consultar multas associadas ao meu veículo de forma rápida e precisa. |
| ST03                | RF        | Eu, como usuário, gostaria de poder pagar multas de trânsito de forma online, com diferentes métodos de pagamento aceitos. |
| ST04                | RF        | Eu, como usuário, gostaria de verificar as informações do meu veículo, incluindo licenciamento e impostos, de forma fácil e conveniente. |
| ST05                | RF        | Eu, como usuário, gostaria de receber dicas de segurança personalizadas para minha moto ou carro, de acordo com as condições de viagem. |
| ST06                | RF        | Eu, como usuário, gostaria de receber notificações em tempo real sobre atualizações nas leis de trânsito e outras informações importantes. |
| ST07                | RF        | Eu, como usuário, gostaria de agendar atendimento presencial no Detran para evitar longas filas e garantir um atendimento mais eficiente. |
| ST08                | RF        | Eu, como usuário, gostaria de poder alterar o endereço associado à minha CNH sem a necessidade de ir pessoalmente a um posto do Detran. |
| ST09                | RF        | Eu, como usuário, gostaria de poder alterar o endereço associado ao meu veículo sem a necessidade de ir pessoalmente a um posto do Detran. |
| ST10                | RF        | Eu, como usuário, gostaria de solicitar autorização de estacionamento para idoso por meio do aplicativo. |
| ST11                | RF        | Eu, como usuário, gostaria de consultar minha CNH para verificar sua validade, categoria e pontos de penalidade. |
| ST12                | RF        | Eu, como usuário, gostaria de consultar informações detalhadas sobre veículos, incluindo histórico de proprietários, débitos pendentes e informações do veículo. |
| ST13                | RF        | Eu, como usuário, gostaria de emitir o CRLV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) de forma rápida e fácil, sem precisar ir pessoalmente ao Detran. |
| ST14                | RF        | Eu, como usuário, gostaria de solicitar a recolocação de placa em caso de perda, roubo ou dano irreparável pelo aplicativo. |
| ST15                | RF        | Eu, como usuário, gostaria de solicitar a segunda via do CRV (DUT) pelo aplicativo em caso de perda ou roubo do documento original. |
| ST16                | RNF       | Eu, como usuário, desejo utilizar o aplicativo em dispositivos Android e iOS. |
| ST17                | RNF       | Eu, como usuário, desejo ter a segurança dos meus dados e dos dados do meu veículo. |

fonte:Autores
## Referências
> First Things First: Prioritizing Requirements. E.Wiegers, Karl. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf Acesso em 02 de Outubro de 2023. 

# Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0    | 30/09/2023 | Adicionado tabela e introduçã0 | Guilherme Nishimura |- |
