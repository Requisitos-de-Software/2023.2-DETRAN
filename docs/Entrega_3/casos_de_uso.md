# Casos de uso

## Introdução 

Casos de uso são uma técnica de modelagem e documentação usada na engenharia de software para descrever como um sistema interage com seus atores (usuários, outros sistemas, etc.). Eles descrevem funcionalidades específicas do sistema, mostrando como os atores interagem com o sistema para alcançar objetivos específicos. Os casos de uso consistem em atores (papéis desempenhados por usuários ou sistemas externos) e os cenários (sequências de ações) que descrevem as interações entre esses atores e o sistema. Eles são frequentemente usados para capturar requisitos funcionais e ajudam a compreender o comportamento do sistema a partir de uma perspectiva do usuário.

## Metodologia

Na elaboração do artefato, empregou-se uma abordagem convencional, baseada na criação de um diagrama de casos de uso seguindo os princípios da UML (Unified Modeling Language). A ferramenta escolhida para essa finalidade foi o LucidChart, um software especializado em diagramação e modelagem que se destaca por sua versatilidade e aplicabilidade em uma ampla gama de contextos de desenvolvimento.

## Componentes 

1) Ator : Um ator é um participante externo que interage com o sistema. Isso pode ser um usuário, outro sistema, ou qualquer entidade que esteja envolvida nas interações com o sistema. Os atores são representados por ícones, como figuras humanas ou caixas, e são nomeados de acordo com o papel que desempenham.(Figura 1).

![Ator](https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/ator-uml.png)

Figura 1: Elemento atores. 

2) Cenario : E o elemento onde e descrito os eventos que acontecem quando um usuário utiliza o sistema,onde todos os casos de usos descritos pelo sistema Normalmente estao dentro do cenário, caso contrário serão considerados fora do escopo do sistema.Normalmente representado por uma caixa (Figura 2).

![Cenario](https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/cenario.png)

Figura 2: Elemento Cenario.

3) Casos de uso: Casos de uso representam ações ou funcionalidades executadas por um usuário ou ator no contexto de um sistema. Esses casos são tipicamente delineados por meio de objetos representados como ovals horizontais (Figura 3) e cada um desses objetos representa uma utilização distinta que um usuário pode fazer do sistema. Dado que essas ações são interações realizadas pelos usuários, é comum a utilização de verbos no infinitivo para descrevê-las, o que torna a representação das funcionalidades mais clara e compreensível.

![casos de uso](https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/usecase-uml.png)

Figura 3: Elemento caso de uso. 

4) Comunicação (ou Ação): Esta categoria envolve ações específicas que um usuário ou ator realiza no contexto de um caso de uso, e pode ser observada na Figura 4. As ações podem ser classificadas em dois tipos distintos:

Inclusão: Quando um caso de uso requer que sua funcionalidade seja executada por meio de outro caso de uso. Em outras palavras, quando um caso de uso A inclui um caso de uso B, ao executar o caso de uso A, o caso de uso B é automaticamente acionado como parte do processo.
Notação no diagrama: <>

Extensão: O caso de uso atual opera normalmente, mas pode incluir etapas adicionais em caso de uso estendido. Isso significa que, se o caso de uso B estiver estendido pelo caso de uso A, ao executar o primeiro, o caso de uso B pode ou não ser ativado, dependendo das condições específicas.
Notação no diagrama: <<>>

![comunicação](https://raw.githubusercontent.com/requisitos-de-software/2023.1-vlc/master/docs/modelagem/img/comunicacao.png)

Figura 4: Elemento comunicação. 

## Casos de uso

![casos de uso](https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-DETRAN/main/assets/casos_de_uso_Detran.png)
 
Figura 5: Diagrama de casos de uso.

Segue abaixo as tabelas com  a especificação dos casos de uso identificados com Use case seguido por uma enumeração referente ao diagrama.

### Use case 01 - Veiculo.

| UseCase 01              | Veiculo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Atores            | Usuário                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Frequencia de uso | Alta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Requisitos        | Abrir ambiente de veiculos.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Fluxo Principal   | 1.O usuario clica em veiculos<br>2.O usuario seleciona se deseja consultar ou emitir algum documento                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Fluxo Alternativo | Não tem.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Fluxos de exceção | Fluxo 1: O usuario clica em consultar debito.<br>1.O sistema solicita a placa do carro e renavam.<br>2.O sistema devolve os debitos do veiculo<br><br><br>Fluxo 2: O usuario clica em consultar as restrições do veiculo.<br><br>1.O sistema solicita a placa do carro e renavam.<br>2.O sistema devolve as restrições do veiculo.<br><br>Fluxo 3: O usuario clica em emitir o CRLV-E.<br><br>1.O sistema exibe os carros disponiveis do usuario.<br>2.O usuario escolhe o veiculo.3.O sistema devolve o crlv-e do veiculo.<br><br><br>Fluxo 4: O usuario clica em transferir o veiculo.<br><br>1.O sistema solicita a placa e o renavam.<br>2.O sistema pede para escolher o veiculo.<br>3.O sistema pede os dados para a transferencia do veiculo.<br>4.O sistema inicia o processo de transferencia de veiculo. |
| Data              | 25/10/2023 |
| Rastreabilidade   | ADD15,ADD16,ADD17,ADD19,ADD23,ADD24 |

Tabela 1: Especificação do caso de uso: Veiculo.

### Use Case 02 - CNH

| UseCase 02              | CNH                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Atores            | Usuário                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Frequencia de uso | Alta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Requisitos        | Abrir ambiente de CNH.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Fluxo Principal   | 1.O usuario clica em CNH<br>2.O usuario seleciona se deseja consultar ou emitir algum documento da carteira nacional de habilitação.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Fluxo Alternativo | Não tem.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Fluxos de exceção | Fluxo 1: O usuario clica em consultar CNH.<br>1.O sistema solicita o login.<br>2.O usuario clica em consultar CNH.<br>3.O sistema devolve a pontuação e os dados do titular<br><br><br><br>Fluxo 2: O usuario clica em solicitar primeira via da cnh.<br><br>1.O sistema solicita o cpf e a data de nascimento.<br>2.O sistema agenda a entrega da primeira via da habilitação.<br><br>Fluxo 3: O solicita clica em solicitar a segunda via da cnh.<br><br>1.O sistema solicita o endereço e os dados do documento.<br>2.O sistema solicita o pagamento.<br>3.O sistema agenda a entrega da segunda via.<br><br><br><br>Fluxo 4: O usuario clica em solicitar CNH definitiva<br><br>1.O sistema verifica a permissao para dirigir do usuario.<br>2.O sistema devolve a CNH do usuario. |
| Data              | 25/10/2023 |
| Rastreabilidade   | ADD18,ADD31|

Tabela 2: Especificação do caso de uso: CNH.

### Use case 03 - Agendamento

| UseCase 03              | Agendamento                                                                                                                                                                                                                                                                  |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Atores            | Usuário                                                                                                                                                                                                                                                                      |
| Frequencia de uso | Alta                                                                                                                                                                                                                                                                         |
| Requisitos        | Abrir ambiente de Agendamento.                                                                                                                                                                                                                                               |
| Fluxo Principal   | 1.O usuario clica em Agendamento<br>2.O usuario entra na pagina de agendamento de serviços do gov.                                                                                                                                                                           |
| Fluxo Alternativo | Não tem.                                                                                                                                                                                                                                                                     |
| Fluxos de exceção | Fluxo 1: O usuario clica em solicitar agendamento.<br>1.O sistema solicita os dados do cidadão.<br>2.O sistema solicita os dados do agendamento.<br>3.O sistema fornece e solicita as datas e horarios disponiveis para o agendamento.<br>4.O sistema realiza o agendamento. |
| Data              | 25/10/2023 |
| Rastreabilidade   | ADD27,ADD34|

Tabela 3: Especificação do caso de uso: Agendamento.

### Use case 04  - Infração

| UC04              | Infração                                                                                                                                                                                                                                                                      |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Atores            | Usuário                                                                                                                                                                                                                                                                       |
| Frequencia de uso | Alta                                                                                                                                                                                                                                                                          |
| Requisitos        | Abrir ambiente de Infração.                                                                                                                                                                                                                                                   |
| Fluxo Principal   | 1.O usuario clica em Infração.<br>2.O usuario solicita a identificação de tipo de infração.                                                                                                                                                                                   |
| Fluxo Alternativo | Não tem.                                                                                                                                                                                                                                                                      |
| Fluxos de exceção | Fluxo 1: O usuario clica em consultar infração.<br>1.O sistema solicita se o usuario deseja identificar,confirmar ou acompanhar algum condutor como infrator.<br>2.O sistema solicita os dados do condutor.<br>3.O sistema devolve a situação das infrações daquele condutor. |
| Data              | 25/10/2023|
| Rastreabilidade   | ADD32,ADD22 |

Tabela 4: Especificação do caso de uso: Infração.


## Historico de versões

| Versão | Data       | Descrição             | Autor              | Revisor             |
| ------ | ---------- | --------------------  | ------------------ | ------------------- |
| 1.0    | 24/10/2023 |Criação do Casos de uso| João Pedro         |                     |