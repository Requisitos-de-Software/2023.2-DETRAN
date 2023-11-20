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
| ENT     | Entrevista                |
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
| NFR | |
| Especificação Suplementar | |

<p align="center">
Tabela 04 - Modelo de Rastreabilidade para requisitos não funcionais <br>
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
