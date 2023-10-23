# Análise de documentos

## Introdução

A técnica de cenários é uma poderosa ferramenta na análise e modelagem de requisitos de software. Ela oferece inúmeras vantagens, como a capacidade de descrever interações detalhadas entre usuários e sistemas, permitindo uma compreensão abrangente do comportamento do software em diferentes situações. Além disso, a modelagem de cenários facilita a identificação de requisitos funcionais e não funcionais, ajuda na validação de requisitos e fornece uma base sólida para a criação de casos de teste.

## Metodologia

Para a criação dos cenários levamos em consideração a notação encontrada em [1], a partir da notação apresentada foi gerado a seguinte tabela para descrição dos cenários:

### ID do Cenário (CX, onde x = 1, 2, 3...) - Título

| Item | Descrição |
|:----:|:---------:|
| Objetivo | Estabelece a finalidade de um cenário. |
| Contexto | Descreve o estado inicial de um cenário, suas précondições, o local (físico) e tempo. Na sua definição podem ser especificadas restrições sobre estes elementos (constraint). |
| Recursos | Identifica os objetos passivos com os quais lidam os atores. Na sua definição podem ser especificadas restrições sobre os objetos a serem lidados pelo cenário (constraint). |
| Atores | Pessoa ou estrutura organizacional que tem um papel no cenário. |
| Episódios | Cada episódio representa uma ação realizada por um ator. |

Tabela 01 - Modelo padrão para descrição de cenários (Fonte: [1])

Obs: Um episódio também pode se referir a outro cenário, o mesmo também pode apresentar restrições ou exceções.

## Bibliografia

[1] Cenários - Rastreamento de Cenários. Disponível em: http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf. Acesso em: 23 de outubro de 2023.

| Versão | Data       | Autor             | Alterações                                          | Revisor        |
| ------ | ---------- | ----------------- | --------------------------------------------------- | -------------- |
| 1.0    | 23/10/2023 | Vitor Borges | Criação do documento | Guilherme |
| 1.1    | 23/10/2023 | Vitor Borges | Adição do modelo padrão para descrição de cenários | Guilherme |