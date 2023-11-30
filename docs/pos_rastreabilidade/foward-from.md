# Foward-from

## 1. Introdução
Rastreabilidade refere-se à capacidade de documentar e seguir as relações entre diferentes elementos ao longo do ciclo de vida de um projeto. Em engenharia de requisitos de software, a rastreabilidade é crucial para garantir a consistência e a compreensão entre requisitos, implementação e testes.<br>
Sendo assim neste artefato utilizamos a técnica "foward-from" (para frente, a partir de) que consiste no relacionamento dos requisitos a a artefatos de desenho e implementação (diagramas, protótipos, estrutura).

## 2. Metodologia
A forward-from pode ser usada para demonstrar as conexões entre requisitos e artefatos gerados nas etapas seguintes do desenvolvimento. No contexto da conexão entre requisitos, o forward-from envolve mapear as dependências entre eles. Isso inclui entender se um requisito está relacionado a outro, se o aprimora, generaliza ou substitui.

## 3. Mapeamento

Na Tabela 1 é possível ver a legenda referente aos artefatos que geraram ou evoluíram algum requisito.

| Legenda | Artefato/Requisito      |
| ------- | ------------------------- |
| AD      | Análise de Documentos     |
| US      | História usuário          |
| ST      | Storytelling              |
| INT     | Entrevista                |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| Q       | Questionário              |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |
| RI      | Requisitos de Interface   |
| RPR     | Requisitos de Produto     |
| RR | Riscos |
| RT | Testes e Validações|

<p align="center">
Tabela 01 - Legendas<br>
(Fonte: Vitor Borges).
</p>

## 4. Requisitos Elicitados

| Número do Requisito | Categoria              | Requisito                                                     |
|---------------------|------------------------|-------------------------------------------------------------|
| ADD1                | RF                     | Baixar o aplicativo em sistemas Android (versão 5 ou superior) e iOS.           |
| ADD2                | RF                     | Permitir cadastrro no Portal de Serviços, exigindo um endereço de e-mail válido.   |
| ADD3                | RF                     | Oferecer opção de alteração de senha no aplicativo.       |
| ADD4                | RF                     | Disponibilizar variedade de serviços relacionados à CNH e veículos.               |
| ADD5                | RNF                    | Garantir compatibilidade com Android 5 ou superior.        |
| ADD6                | RNF                    | Assegurar compatibilidade com iOS.                          |
| ADD7                | RI                     | Projetar interface fácil de usar para cadaAstro no Portal de Serviços.             |
| ADD8                | RI                     | Criar interface para alteração de senha de forma intuitiva e segura.              |
| ADD9                | RI                     | Apresentar opções de serviço de forma clara e acessível aos usuários.            |
| ADD10               | RPR                    | Garantir desempenho aceitável em dispositivos Android e iOS.                        |
| ADD11               | RR                     | Risco associado à segurança da alteração de senha e envio de e-mails.             |
| ADD12               | RT                     | Realizar testes para validação de funcionalidades do aplicativo.                  |
| ADD13               | RF                     | Deve ser possível baixar os boletos com os débitos do meu veículo.               |
| ADD14               | RF                     | Deve ser possível realizar o pagamento dos boletos com os débitos do meu veículo.|
| ADD15               | RF                     | Deve ser possível baixar os documentos do meu veículo.    |
| ADD16               | RF                     | Deve ser possível consultar os dados de veículos a partir do renavam.             |
| ADD17               | RF                     | Deve ser possível consultar os dados de veículos a partir da placa.              |
| ADD18               | RF                     | Deve ser possível baixar a minha CNH digital.             |
| ADD19               | RF                     | Deve ser possível realizar a transferência de veículo.    |
| ADD20               | RNF                    | O aplicativo deverá guardar as informações de login do usuário.                   |
| ADD21                | RF                     | Receber notificações automáticas sobre a proximidade da expiração da carteira de motorista. | 
| ADD22                | RF                     | Consultar multas associadas ao veículo de forma rápida e precisa. | 
| ADD23                | RF                     | Pagar multas de trânsito online, utilizando diferentes métodos de pagamento. | 
| ADD24                | RF                     | Verificar informações do veículo, incluindo licenciamento e impostos, de forma fácil e conveniente. | 
| ADD25                | RF                     | Receber dicas de segurança personalizadas para o veículo, baseadas nas condições de viagem. | 
| ADD26                | RF                     | Receber notificações em tempo real sobre atualizações nas leis de trânsito e outras informações relevantes. | 
| ADD27                | RF                     | Agendar atendimento presencial no Detran para evitar filas e garantir eficiência no atendimento. | 
| ADD28                | RF                     | Alterar o endereço associado à CNH sem a necessidade de ir pessoalmente a um posto do Detran. | 
| ADD29                | RF                     | Alterar o endereço associado ao veículo sem a necessidade de ir pessoalmente a um posto do Detran. | 
| ADD30                | RF                     | Solicitar autorização de estacionamento para idoso por meio do aplicativo. | 
| ADD31                | RF                     | Consultar a CNH para verificar sua validade, categoria e pontos de penalidade. | 
| ADD32                | RF                     | Consultar informações detalhadas sobre veículos, incluindo hiAstórico de proprietários, débitos pendentes e informações do veículo. | 
| ADD33                | RF                     | Emitir o CRLV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) de forma rápida e fácil, sem precisar ir pessoalmente ao Detran. | 
| ADD34                | RF                     | Solicitar a recolocação de placa em caso de perda, roubo ou dano irreparável pelo aplicativo. |

<p align="center">
Tabela 02 - Requisitos elicitados <br>
(Fonte: Grupo 07)
</p>

## 5. Rastreabilidade

Para rastrear cada requisito foi utilizado os seguintes modelos de tabela:

| ID Requisito | Descrição |
| :----------: | :-------: |
| Épico | |
| História de Usuário | |
| Léxico | |
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | |
| Funcionalidade | Implementado ou Não Implementado |

<p align="center">
Tabela 03 - Modelo de Rastreabilidade para requisitos funcionais <br>
(Fonte: Vitor Borges)
</p>

| ID Requisito | Descrição |
| :----------: | :-------: |
| Épico | |
| NFR | |
| Especificação Suplementar | |

<p align="center">
Tabela 04 - Modelo de Rastreabilidade para requisitos não funcionais <br>
(Fonte: Vitor Borges)
</p>

## 5.1 Requisitos Funcionais

| ADD1 | Baixar o aplicativo em sistemas Android (versão 5 ou superior) e iOS. |
| :----------: | :-------: |
| Épico | Compatibilidade |
| História de Usuário | |
| Léxico | (L1)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l1-usuario]<br> (L5)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l5-baixar] <br> (L14)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l14-compativel] |
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (AD)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/analise_de_documentos/#9-tabela-de-requisitos] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 04 - Rastreabilidade requisito ADD1 <br>
(Fonte: Vitor Borges)
</p>

| ADD2 | Permitir cadastro no Portal de Serviços, exigindo um endereço de e-mail válido. |
| :----------: | :-------: |
| Épico | Registro e Autenticação do Usuário |
| História de Usuário | |
| Léxico | (L1)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l1-usuario]<br> (L13)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l13-valido]<br> (L15)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l15-e-mail] |
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (AD)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/analise_de_documentos/#9-tabela-de-requisitos] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 05 - Rastreabilidade requisito ADD2 <br>
(Fonte: Vitor Borges)
</p>

| ADD3 | Oferecer opção de alteração de senha no aplicativo. |
| :----------: | :-------: |
| Épico | Registro e Autenticação do Usuário |
| História de Usuário | |
| Léxico | (L1)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l1-usuario]<br> (L13)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l8-alterar]<br> (L15)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l15-e-mail]|
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (AD)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/analise_de_documentos/#9-tabela-de-requisitos] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 06 - Rastreabilidade requisito ADD3 <br>
(Fonte: Vitor Borges)
</p>

| ADD4 | Disponibilizar variedade de serviços relacionados à CNH e veículos. |
| :----------: | :-------: |
| Épico | Serviços de CNH, Serviços de Veículos |
| História de Usuário | (US5)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#35-historia-5-consulta-de-processo-de-habilitacao] |
| Léxico | (L1)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l1-usuario]<br> |
| Casos de uso | |
| Cenários | (C01)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/cenarios/#c01-baixar-documentos-do-veiculo]<br> (C02)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/cenarios/#c02-gerar-cnh-digital]<br> (C03)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/cenarios/#c03-consultar-infracoes]<br> (C04)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/cenarios/#c04-emitir-crlv-e] |
| Artefatos de Elicitação | (AD)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/analise_de_documentos/#9-tabela-de-requisitos] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 07 - Rastreabilidade requisito ADD4 <br>
(Fonte: Vitor Borges)
</p>

| ADD13 | Deve ser possível baixar os boletos com os débitos do meu veículo. |
| :----------: | :-------: |
| Épico | Serviços de Veículos |
| História de Usuário | (US10)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#310-historia-10-consultar-dados-do-veiculo] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L5)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l5-baixar]<br> |
| Casos de uso | |
| Cenários | (C03)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/cenarios/#c03-consultar-infracoes] |
| Artefatos de Elicitação | (INT)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/entrevista/#3-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 08 - Rastreabilidade requisito ADD13 <br>
(Fonte: Vitor Borges)
</p>

| ADD14 | Deve ser possível realizar o pagamento dos boletos com os débitos do meu veículo. |
| :----------: | :-------: |
| Épico | Serviços de Veículos, Pagamento e Multas |
| História de Usuário | |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L6)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l6-pagar]<br> |
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (INT)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/entrevista/#3-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 09 - Rastreabilidade requisito ADD14 <br>
(Fonte: Vitor Borges)
</p>

| ADD15 | Deve ser possível baixar os documentos do meu veículo. |
| :----------: | :-------: |
| Épico | Serviços de Veículos |
| História de Usuário | (US10)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#310-historia-10-consultar-dados-do-veiculo] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L5)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l5-baixar] |
| Casos de uso | (UC2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-02-consultar-veiculo] |
| Cenários | |
| Artefatos de Elicitação | (INT)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/entrevista/#3-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 10 - Rastreabilidade requisito ADD15 <br>
(Fonte: Vitor Borges)
</p>

| ADD16 | Deve ser possível consultar os dados de veículos a partir do renavam. |
| :----------: | :-------: |
| Épico | Serviços de Veículos |
| História de Usuário | (US10)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#310-historia-10-consultar-dados-do-veiculo] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L7)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l7-consultar] |
| Casos de uso | (UC2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-02-consultar-veiculo] |
| Cenários | |
| Artefatos de Elicitação | (INT)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/entrevista/#3-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 11 - Rastreabilidade requisito ADD16 <br>
(Fonte: Vitor Borges)
</p>

| ADD17 | Deve ser possível consultar os dados de veículos a partir da placa. |
| :----------: | :-------: |
| Épico | Serviços de Veículos |
| História de Usuário | (US10)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#310-historia-10-consultar-dados-do-veiculo] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L7)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l7-consultar] |
| Casos de uso | (UC2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-02-consultar-veiculo] |
| Cenários | |
| Artefatos de Elicitação | (INT)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/entrevista/#3-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 12 - Rastreabilidade requisito ADD17 <br>
(Fonte: Vitor Borges)
</p>

| ADD18 | Deve ser possível baixar a minha CNH digital. |
| :----------: | :-------: |
| Épico | Serviços de CNH |
| História de Usuário | (US7)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#37-historia-7-emitir-carteira-nacional-de-habilitacao-eletronica-cnh-e] |
| Léxico | (L2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l2-cnh]<br>(L5)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l5-baixar]<br>(L17)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l17-expirado] |
| Casos de uso | (UC3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-03-consultar-cnh] |
| Cenários | (C2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/cenarios/#c02-gerar-cnh-digital] |
| Artefatos de Elicitação | (INT)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/entrevista/#3-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 13 - Rastreabilidade requisito ADD18 <br>
(Fonte: Vitor Borges)
</p>

| ADD19 | Deve ser possível realizar a transferência de veículo. |
| :----------: | :-------: |
| Épico |  |
| História de Usuário | (US7)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#37-historia-7-emitir-carteira-nacional-de-habilitacao-eletronica-cnh-e] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L11)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l11-solicitar]<br> |
| Casos de uso | (UC2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-02-consultar-veiculo] |
| Cenários |  |
| Artefatos de Elicitação | (INT)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/entrevista/#3-requisitos-elicitados] |
| Funcionalidade | Não Implementado |

<p align="center">
Tabela 14 - Rastreabilidade requisito ADD19 <br>
(Fonte: Vitor Borges)
</p>

| ADD21 | Consultar multas associadas ao veículo de forma rápida e precisa. |
| :----------: | :-------: |
| Épico | Notificações e Atendimento ao Cliente |
| História de Usuário | |
| Léxico | (L2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l2-cnh]<br>(L9)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l9-receber]<br>(L17)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l17-expirado] |
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Não Implementado |

<p align="center">
Tabela 15 - Rastreabilidade requisito ADD21 <br>
(Fonte: Vitor Borges)
</p>

| ADD22 | Receber notificações automáticas sobre a proximidade da expiração da carteira de motorista. |
| :----------: | :-------: |
| Épico | Notificações e Atendimento ao Cliente |
| História de Usuário | (US8)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#38-historia-8-emitir-infracoes]<br>(US10)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#310-historia-10-consultar-dados-do-veiculo] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L7)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l7-consultar]<br>(L16)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l16-multa] |
| Casos de uso | (UC5)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-05-verificar-infracoes] |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Não Implementado |

<p align="center">
Tabela 16 - Rastreabilidade requisito ADD22 <br>
(Fonte: Vitor Borges)
</p>

| ADD23 | Pagar multas de trânsito online, utilizando diferentes métodos de pagamento. |
| :----------: | :-------: |
| Épico | Pagamento e Multas |
| História de Usuário | (US8)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#38-historia-8-emitir-infracoes] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L6)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l6-pagar]<br>(L16)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l16-multa] |
| Casos de uso | (UC2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-02-consultar-veiculo] |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Não Implementado |

<p align="center">
Tabela 17 - Rastreabilidade requisito ADD23 <br>
(Fonte: Vitor Borges)
</p>

| ADD24 | Verificar informações do veículo, incluindo licenciamento e impostos, de forma fácil e conveniente. |
| :----------: | :-------: |
| Épico |  |
| História de Usuário | (US10)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#310-historia-10-consultar-dados-do-veiculo] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L7)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l7-consultar]<br> |
| Casos de uso | (UC2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-02-consultar-veiculo] |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 18 - Rastreabilidade requisito ADD24 <br>
(Fonte: Vitor Borges)
</p>

| ADD26 | Receber notificações em tempo real sobre atualizações nas leis de trânsito e outras informações relevantes. |
| :----------: | :-------: |
| Épico | Notificações e Atendimento ao Cliente |
| História de Usuário | |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L9)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l9-receber]<br> |
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Não Implementado |

<p align="center">
Tabela 19 - Rastreabilidade requisito ADD26 <br>
(Fonte: Vitor Borges)
</p>

| ADD27 | Agendar atendimento presencial no Detran para evitar filas e garantir eficiência no atendimento. |
| :----------: | :-------: |
| Épico | Notificações e Atendimento ao Cliente |
| História de Usuário | (US1)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#31-historia-1-agendamento-de-atendimento-presencial] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L10)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l10-agendar]<br> |
| Casos de uso | (UC4)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-04-consultar-agendamento] |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 20 - Rastreabilidade requisito ADD27 <br>
(Fonte: Vitor Borges)
</p>

| ADD28 | Alterar o endereço associado à CNH sem a necessidade de ir pessoalmente a um posto do Detran. |
| :----------: | :-------: |
| Épico | Notificações e Atendimento ao Cliente |
| História de Usuário | (US2)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#32-historia-2-alteracao-de-endereco-da-carteira-nacional-de-habilitacao-cnh] |
| Léxico | (L2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l2-cnh]<br>(L8)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l8-alterar]|
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Não Implementado |

<p align="center">
Tabela 21 - Rastreabilidade requisito ADD28 <br>
(Fonte: Vitor Borges)
</p>

| ADD29 | Alterar o endereço associado ao veículo sem a necessidade de ir pessoalmente a um posto do Detran. |
| :----------: | :-------: |
| Épico | Notificações e Atendimento ao Cliente |
| História de Usuário | (US2)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#32-historia-2-alteracao-de-endereco-da-carteira-nacional-de-habilitacao-cnh] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L8)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l8-alterar]|
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Não Implementado |

<p align="center">
Tabela 22 - Rastreabilidade requisito ADD29 <br>
(Fonte: Vitor Borges)
</p>

| ADD30 | Solicitar autorização de estacionamento para idoso por meio do aplicativo. |
| :----------: | :-------: |
| Épico | Notificações e Atendimento ao Cliente |
| História de Usuário | (US4)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#34-historia-4-autorizacao-de-estacionamento-para-idoso] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L11)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l11-solicitar]|
| Casos de uso | |
| Cenários | |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Não Implementado |

<p align="center">
Tabela 23 - Rastreabilidade requisito ADD30 <br>
(Fonte: Vitor Borges)
</p>

| ADD31 | Consultar a CNH para verificar sua validade, categoria e pontos de penalidade. |
| :----------: | :-------: |
| Épico | Serviços de CNH |
| História de Usuário | (US9)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#39-historia-9-consultar-dados-da-carteira-nacional-de-habilitacao-cnh] |
| Léxico | (L2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l2-cnh]<br>(L7)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l7-consultar]<br>(L13)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l13-valido]|
| Casos de uso | (UC3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-03-consultar-cnh] |
| Cenários | (C2)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/cenarios/#c02-gerar-cnh-digital] |
| Artefatos de Elicitação | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 24 - Rastreabilidade requisito ADD31 <br>
(Fonte: Vitor Borges)
</p>

| ADD32 | Consultar informações detalhadas sobre veículos, incluindo histórico de proprietários, débitos pendentes e informações do veículo. |
| :----------: | :-------: |
| Épico | Serviços de Veículos |
| História de Usuário | (US9)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#39-historia-9-consultar-dados-da-carteira-nacional-de-habilitacao-cnh] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L7)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l7-consultar]<br>(L13)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l13-valido]|
| Casos de uso | (UC5)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-05-verificar-infracoes] |
| Cenários | | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 25 - Rastreabilidade requisito ADD32 <br>
(Fonte: Vitor Borges)
</p>

| ADD33 | Emitir o CRLV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) de forma rápida e fácil, sem precisar ir pessoalmente ao Detran. |
| :----------: | :-------: |
| Épico | Serviços de Veículos |
| História de Usuário | (US3)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#33-historia-3-emissao-do-certificado-de-registro-e-licenciamento-de-veiculo-eletronico-crlv-e] |
| Léxico | (L3)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l3-veiculo]<br>(L12)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l12-emitir]<br>(L18)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l18-crlv]|
| Casos de uso | |
| Cenários | | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 26 - Rastreabilidade requisito ADD33 <br>
(Fonte: Vitor Borges)
</p>

| ADD34 | Solicitar a recolocação de placa em caso de perda, roubo ou dano irreparável pelo aplicativo. |
| :----------: | :-------: |
| Épico | Serviços de Veículos |
| História de Usuário | (US3)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/historias_de_usuarios/#33-historia-3-emissao-do-certificado-de-registro-e-licenciamento-de-veiculo-eletronico-crlv-e] |
| Léxico | (L11)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/lexico/#l11-solicitar] |
| Casos de uso | (UC4)[https://requisitos-de-software.github.io/2023.2-DETRAN/3_modelagem/casos_de_uso/#use-case-04-consultar-agendamento] |
| Cenários | | (ST)[https://requisitos-de-software.github.io/2023.2-DETRAN/2_elicita%C3%A7%C3%A3o/storytelling/#4-requisitos-elicitados] |
| Funcionalidade | Implementado |

<p align="center">
Tabela 27 - Rastreabilidade requisito ADD34 <br>
(Fonte: Vitor Borges)
</p>

## 5.2 Requisitos Não Funcionais

| ADD5 | Garantir compatibilidade com Android 5 ou superior. |
| :----------: | :-------: |
| Épico | Compatibilidade |
| NFR | (Confiabilidade)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/NFR/#confiabilidade] |
| Especificação Suplementar | |

<p align="center">
Tabela 28 - Rastreabilidade requisito ADD5 <br>
(Fonte: Vitor Borges)
</p>

| ADD6 | Garantir Assegurar compatibilidade com iOS. |
| :----------: | :-------: |
| Épico | Compatibilidade |
| NFR | (Confiabilidade)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/NFR/#confiabilidade] |
| Especificação Suplementar | |

<p align="center">
Tabela 29 - Rastreabilidade requisito ADD6 <br>
(Fonte: Vitor Borges)
</p>

| ADD20 | Registro e Autenticação do Usuário. |
| :----------: | :-------: |
| Épico | Compatibilidade |
| NFR | (Confiabilidade)[https://requisitos-de-software.github.io/2023.2-DETRAN/4_modelagem_agil/NFR/#confiabilidade] |
| Especificação Suplementar | |

<p align="center">
Tabela 30 - Rastreabilidade requisito ADD6 <br>
(Fonte: Vitor Borges)
</p>

## Bibliografia
> Requisitos Aula 26 - Professores: Milene Serrano e Maurício Serrano 

## Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0    | 19/11/2023 | Introdução sobre o tema | Vitor Borges | João Pedro, Guilherme |
| 1.1    | 19/11/2023 | Descrevendo metodologia | Vitor Borges | João Pedro, Guilherme |
| 1.2    | 19/11/2023 | Adicionado legenda para os artefatos e requisitos | Vitor Borges | João Pedro, Guilherme |
| 1.3    | 19/11/2023 | Adicionado modelos de tabela para rastreabilidade | Vitor Borges | João Pedro, Guilherme |
