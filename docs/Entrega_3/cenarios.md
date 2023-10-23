# Cenários

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

## Descrição dos Cenários

### C01 - Baixar documentos do veículo

| Item | Descrição |
|:----:|:---------:|
| Objetivo | Realizar download dos documentos do veículo |
| Contexto | Local: casa, blitz policial <br> Tempo: durante o dia <br> Restrições: acesso a internet e possuir o app instalado |
| Recursos | Celular, Internet |
| Atores | Usuário |
| Episódios | 1. Usuário deseja imprimir uma cópia fisíca do documento para deixar em seu veículo. <br> 2. Usuário deseja enviar as informações do veículo para um terceiro <br> 3. Usuário necessita apresentar o documento em um orgão do governo ou em uma blitz policial |

Tabela 02 - Descrição do cenário 01 (Fonte: Vitor Borges)

### C02 - Gerar CNH digital

| Item | Descrição |
|:----:|:---------:|
| Objetivo | Ter a disposição uma versão digital de sua própria CNH |
| Contexto | Local: casa, blitz policial <br> Tempo: durante o dia <br> Restrições: acesso a internet e possuir o app instalado |
| Recursos | Celular, Internet |
| Atores | Usuário |
| Episódios | 1. Usuário deseja visualizar se sua CNH está próxima da data de renovação <br> 2. Usuário deseja consultar as informações de sua CNH <br> 3. Usuário necessita apresentar um documento de identificação com foto <br> 4. Usuário necessita apresentar o documento em um orgão do governo ou em uma blitz policial |

Tabela 03 - Descrição do cenário 02 (Fonte: Vitor Borges)

## Bibliografia

[1] Cenários - Rastreamento de Cenários. Disponível em: http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf. Acesso em: 23 de outubro de 2023.

| Versão | Data       | Autor             | Alterações                                          | Revisor        |
| ------ | ---------- | ----------------- | --------------------------------------------------- | -------------- |
| 1.0    | 23/10/2023 | Vitor Borges | Criação do documento | Guilherme |
| 1.1    | 23/10/2023 | Vitor Borges | Adição do modelo padrão para descrição de cenários | Guilherme |
| 1.2    | 23/10/2023 | Vitor Borges | Adição de cenários | Guilherme |