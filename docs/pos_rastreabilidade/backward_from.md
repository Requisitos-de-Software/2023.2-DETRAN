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

<p align="center">
Tabela 1 - Tabelas de requisitos funcionais<br>
(Fonte: João Gabriel Elvas)
</p>

## Tabelas de requisitos não funcionais
| Novo ID | Descrição | Rastreabilidade | Implementação |
|---------|-----------|------------------|---------------|
| RNF01.1 | Garantir compatibilidade com Android 5 ou superior | ADD1,ADD1,ST16,ES09,L14 | Implementado |
| RNF02.1 | Assegurar compatibilidade com iOS | ADD1,ADD1,ST16,ES09,L14 | Implementado |
| RNF03.1 | O aplicativo deverá guardar as informações de login do usuário | ADD20 | Implementado |
| RNF04.1 | O aplicativo deve fornecer o campo errado quando o usuário errar o login | UC01 | Implementado |
<p align="center">
Tabela 2 - Tabelas de requisitos não funcionais<br>
(Fonte: João Gabriel Elvas)
</p>

## Elos

Com base nos rquisitos será feito a representação dos elos seguindo modelo de Toranzo igual a tabela 3 abaixo:

| Termo             | Descrição                                                                               |
|:-----------------:|:---------------------------------------------------------------------------------------:|
| Satisfação        | A relação entre a classe de origem e a classe de destino é influenciada pela satisfação da primeira com a segunda. |
| Recurso           | A dependência entre a classe de origem e a classe de destino está associada aos recursos que a primeira utiliza da segunda. |
| Responsabilidade  | Documenta a participação, responsabilidade e ação de indivíduos em relação aos artefatos específicos. |
| Representação     | Envolve a captura da modelagem ou representação dos requisitos em outras linguagens ou formas de expressão. |
| Alocado           | A classe de origem está vinculada à classe de destino, representando um subsistema alocado ou relacionado. |
| Agregação         | Destaca a forma como os elementos se agregam ou se compõem. |
<p align="center">
Tabela 3 - Descrição dos termos<br>
(Fonte: Guilherme Nishimura da Silva)
</p>



## Tabela de elo
| id | Requisito | Tipo de Elo |
| -- | --------- | ----------- |
| ELO01 | RF01.1 | Representação: C03 representa ST02,UC02,R02 <br> Agregação:L7 agrega RF01 <br>  |
| ELO02 | RF02.1 | Satisfação: P02 Satisfaz INT02,ADD14,ST03,UC02  <br> Agregação: L7 agrega RF02.1 <br>  |
| ELO03 | RF03.1 | Representação: ADD33 representa ST13,UC02,C04,L18,US03 |
| ELO04 | RF04.1 | Representação: ADD16 representa PE04,ADD16,UC02 <br> Agregação: L7 agrega RF04.1 <br> |
| ELO05 | RF05.1 | Representação: ADD27 representa RQ5,US01,ST07 |
| ELO06 | RF06.1 | Recurso:ST15 depende de RF01.1  |
| ELO07 | RF07.1 | Agregação:  L11 satisfaz UC03|
| ELO08 | RF08.1 |Representação: ADD29 representa ST09 <br> Satisfação:L8 satisfaz RF08.1 <br>  |
| ELO09 | RF09.1 | Recurso: L8 depende de RF12.1 |
| ELO10 | RF10.1 | Agregação: ST18 agrega ST17 |
| ELO11 | RF11.1 | Representação: ADD02 representa UC01 |
| ELO12 | RF12.1 |  Agregação: US11 agrega RNF02|
| ELO13 | RF13.1 | Representação: ADD30 representam ST10,L11,US04 <br> Agregação: L11 agrega ST10 <br>  |
| ELO14 | RF14.1 | Representação: ADD04 representa PE06,RQ3,ADD18 ,ADD31,ST11,UC03,C02,US07 E US09 |
| ELO15| RNF01.1 | Representação: ADD1 representa ADD1,ST16,ES09, E US09 <br> Agregação: L14 agrega ST10 <br>  |
| ELO16 | RNF01.1 | Representação: ADD1 representa ADD1,ST16,ES09, E US09 <br> Agregação: L14 agrega ST10 <br>  |
| ELO17 | RNF02.1 | Recurso: ADD20 depende de RF12.1  |
| ELO18 | RNF03.1 | Agregação: UC01 agrega RNF03.1  |
<p align="center">
Tabela 4 -Elo <br>
(Fonte: Guilherme Nishimura)
</p>



## Bibliografia

> SERRANO, Milene. Slides da aula 26. Aula 26 da disciplina Requisitos de Software. Universidade de Brasília, Brasília, acesso em 19/11/2023

> POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals. 2ª ed. New York: Springer, 2010.

## Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0    | 18/11/2023 | Criação do documento | João Gabriel Elvas | Guilherme Nishimura |
| 1.1    | 20/11/2023 | Adição de elos | Guilherme Nishimura | João Gabriel Elvas |

