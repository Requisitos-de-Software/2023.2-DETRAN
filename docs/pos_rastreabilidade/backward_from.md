# Backward-From

## Introdução
Este artefato aborda o método de rastreabilidade backward-from, uma técnica essencial para vincular os requisitos elicitados durante o projeto às suas respectivas fontes. A rastreabilidade, por sua vez, representa a habilidade de rastrear os requisitos ao longo de todo o ciclo de vida no sistema.

## Metodologia
Ao aplicar o método backward-from, além de suas peculiaridades, adotamos o meta-modelo de Toranzo, classificando os requisitos elicitados pelo grupo em níveis e elos.

* Ambiental: informações provenientes do ambiente e contexto nos quais a organização está inserida;
* Organizacional: informações relacionadas à organização;
* Gerencial: informações que auxiliam na gestão do projeto;
* Desenvolvimento: informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento.
* Satisfação: a classe de origem depende da satisfação com a classe de destino.
* Recurso: a classe de origem depende de recursos da classe de destino.
* Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
* Representação: captura a representação ou modelagem dos requisitos em outras linguagens.
* Alocado: a classe de origem está relacionada à classe de destino, que representa um subsistema.
* Agregação: indica a "composição" de elementos.
* Para auxiliar na elaboração do meta-modelo de Toranzo, desenvolvemos as Tabelas 1 e 2, as quais segmentam os requisitos a serem rastreados em funcionais (RF) e não-funcionais (RNF).

Legendas:

* RF: Requisito funcional
* RNF: Requisito não-funcional

## Tabelas de requisitos funcionais

| Novo ID | Descrição | Rastreabilidade | Implementação |
|---------|-----------|------------------|---------------|
| RF01.1   | Consultar débitos e infrações do veículo | RQ2,ST02,UC02,C03,L7 | Implementado |
| RF02.1   | Realizar pagamento de débitos | PE02,ADD14,ST03,UC02,L7 | Implementado |
| RF03.1   | Consultar e Emitir o CRLV-e | RQ4,ADD33,ST13,UC02,C04,L18,US03 | Implementado |
| RF04.1   | Consultar e Emitir o Renavam | PE04,ADD16,UC02,L7,US10 | Implementado |
| RF05.1   | Realizar agendamento no Detran | RQ5,ADD27,ST07,UC04,L10,US01 | Implementado |
| RF06.1   | Solicitar primeira via do Dut | ST15 | Implementado |
| RF07.1   | Solicitar segunda via da CNH | UC03,L11 | Implementado |
| RF09.1   | Alterar o endereço do veículo | ADD29,ST09,L8 | Implementado |
| RF10.1   | Alterar dados de usuário | L8 | Implementado |
| RF11.1   | Consultar dados do veículo | PE04,PE05,ADD16,ADD17,L3,US10 | Implementado |
| RF12.1   | Realizar Cadastro e Login do usuário | ADD02,ADD02,UC01 | Implementado |
| RF13.1   | Oferecer funcionalidade de transferência de pontuação | US11 | Incompleto |
| RF14.1   | Solicitar autorização de estacionamento para idoso | ADD30,ST10,L11,US04 | Implementado |
| RF15.1   | Consultar e emitir CNH Digital | ADD04,PE06,RQ3,ADD18 E ADD31,ST11,UC03,C02,L2,US07 E US09 | Implementado |

## Tabelas de requisitos não funcionais
| Novo ID | Descrição | Rastreabilidade | Implementação |
|---------|-----------|------------------|---------------|
| RNF01.1 | Garantir compatibilidade com Android 5 ou superior | ADD1,ADD1,ST16,ES09,L14 | Implementado |
| RNF02.1 | Assegurar compatibilidade com iOS | ADD1,ADD1,ST16,ES09,L14 | Implementado |
| RNF03.1 | O aplicativo deverá guardar as informações de login do usuário | ADD20 | Implementado |
| RNF04.1 | O aplicativo deve fornecer o campo errado quando o usuário errar o login | UC01 | Implementado |


 Conforme os slides 19 e 21 da aula 26 da professora Milene Serrano, os níveis são:
Para a execução deste método, utilizamos os slides da aula 26 da professora Milene Serrano, juntamente com o livro "Requirements Engineering Fundamentals" de Klaus Pohl e Chris Rupp.
