# Verificação Backward-From

# Introdução
A verificação de software é um processo sistemático de avaliação e revisão do código fonte, design e documentação de um programa de computador com bjetivo principal de garantir que o software atenda aos requisitos especificados e que funcione conforme o esperado. 

Esse documento tem o objetivo de documentar as verificações realizadas no artefato de [Backward-from](https://requisitos-de-software.github.io/2023.2-DETRAN/pos_rastreabilidade/backward_from/). O documento irá abordar através do uso de uma checklist para verificar os items do artefato.

# Objetivo

O artefato de verificação Backward-From tem o objetivo de documentar se o artefato foi realizado e se foi feito da maneira correta seguindo os padrões gerais estabelecidos pela disciplina e se os itens do artefato em questão foram realizados da maneira correta.

# Tabela de verificação

## Verificação Geral do padrão do projeto

*Tabela 1: Checklist para a verificação geral do padrão do projeto*

| ID  | Conteudo                                                                                       | Possui | Qualidade  | Comentario                                  |
| --- | ---------------------------------------------------------------------------------------------- | ------ | ---------- | ------------------------------------------- |
| 1   | O artefato possui autor?                                                                       | sim    | Excelente  |                                             |
| 2   | O artefato possui revisor?                                                                     | sim    | Excelente  |                                             |
| 3   | O histórico de versão está padronizado?                                                        | sim    | Excelente  |                                             |
| 4   | O artefato possui referências bibliográficas?                                                  | sim    | Excelente  |                                             |
| 5   | O artefato possui tabelas e imagens com legenda e fonte, e elas são chamadas dentro dos texto? | Sim    | Boa  |             As tabela não são chamadas dentro dos textos.                                |
| 6   | O artefato possui um texto fazendo uma introdução?                                             | Sim    | Excelente  |                                             |
| 7   | O artefato possui links para os outros artefatos?                                              | Não        | Ruim  | Este item deveria ser atendido, pois como é um artefato de pós-rastreabilidade os requisitos das tabelas deveriam ter hyperlinks para facilitar essa rastreabilidade propriamente dita. |


*Fonte: Grupo 7*

## Verificação expecifica do artefato

| ID  | Conteudo                                                                                       | Possui | Qualidade  | Comentario                                  |
|----|-----------|-----------|-------------|-------------|
| 01 | Os requisito demonstrados no artefato estão sendo interligados com as suas fontes? | sim   | boa  | Os requisitos estão interligados com as fontes porém acredito se inserirmos o nome do artefato juntamente com o ID do requisito, ficaria mais fácil realizar a rastreabilidade dos requisitos           |
| 02 | Os requisitos não funcionais presentes no artefato realmente são requisitos não funcionais ou estão sendo colocados erroneamente nessa categoria de requisitos? |  Sim   |  Boa |  O requisito RNF03.1 poderia ser descrito como "O aplicativo deverá lembrar as informações de login do usuário após ele realizar o primeiro login na plataforma para facilitar logins futuros". A descrição desse requisito está um pouco ambígua     |
| 03 | As informações rastreadas estão classificadas nos níveis propostos no [meta-modelo de Toranzo, p. 9](https://www-di.inf.puc-rio.br/~julio/rastre.pdf)?  | sim | Excelente |                                             |
| 04 | Os elos do artefato são de algum dos tipos: Satisfação, Recurso, Responsabilidade, Representação, Alocação e Agregação? |  sim   |  Excelente |                                             | 
| 05 | Os tipos dos elos do artefato estão caracterizados da forma correto, seguindo o [meta-modelo de Toranzo, p. 9](https://www-di.inf.puc-rio.br/~julio/rastre.pdf)? |  sim   |  Excelente |                                             | 
| 04 | Os requisitos do artefato estão caracterizados em implementados ou não implementados? |   Sim  | Boa  | Existe um requisito que está caracterizado como "incompleto", sendo assim a caracterização ideal seria "Não implementado"                                      |  

*Fonte: Pedro Campos*

## Considerações

- Acredito que fizemos um bom artefato no geral, porém poderíamos adicionar hyperlinks, fazer o ajuste na descriação do requisito não funcional RNF03.1 e mudar a classificação do requisito caracterizado como "Incompleto".

## Vídeo da inspeção

[Vídeo do youtube](https://youtu.be/3hBZwBBZXT8)

## Bibliografia

> Rastreabilidade de requisitos, PUC-Rio. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em 03/12/2023.

# Historico de versão

| Versão | Data       | Descrição | Autor               |             Revisor |
|--------|------------|-----------|---------------------|---------------------|
| 1.0    | 03/12/2023 | Criação do documento        | [Pedro Campos](https://github.com/pedrocampos0) |   Vitor       |
  