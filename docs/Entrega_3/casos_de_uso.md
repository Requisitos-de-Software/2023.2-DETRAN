# Casos de uso

## Introdução 

Casos de uso são uma técnica de modelagem e documentação usada na engenharia de software para descrever como um sistema interage com seus atores (usuários, outros sistemas, etc.). Eles descrevem funcionalidades específicas do sistema, mostrando como os atores interagem com o sistema para alcançar objetivos específicos. Os casos de uso consistem em atores (papéis desempenhados por usuários ou sistemas externos) e os cenários (sequências de ações) que descrevem as interações entre esses atores e o sistema. Eles são frequentemente usados para capturar requisitos funcionais e ajudam a compreender o comportamento do sistema a partir de uma perspectiva do usuário.

## Metodologia

Na elaboração do artefato, empregou-se uma abordagem convencional, baseada na criação de um diagrama de casos de uso seguindo os princípios da UML (Unified Modeling Language). A ferramenta escolhida para essa finalidade foi o LucidChart, um software especializado em diagramação e modelagem que se destaca por sua versatilidade e aplicabilidade em uma ampla gama de contextos de desenvolvimento.

## Componentes 

1) Ator : Um ator é um participante externo que interage com o sistema. Isso pode ser um usuário, outro sistema, ou qualquer entidade que esteja envolvida nas interações com o sistema. Os atores são representados por ícones, como figuras humanas ou caixas, e são nomeados de acordo com o papel que desempenham.(Figura 1).

2) Cenario : E o elemento onde e descrito os eventos que acontecem quando um usuário utiliza o sistema,onde todos os casos de usos descritos pelo sistema Normalmente estao dentro do cenário, caso contrário serão considerados fora do escopo do sistema.Normalmente representado por uma caixa (Figura 2).

3) Casos de uso: Casos de uso representam ações ou funcionalidades executadas por um usuário ou ator no contexto de um sistema. Esses casos são tipicamente delineados por meio de objetos representados como ovals horizontais (Figura 3) e cada um desses objetos representa uma utilização distinta que um usuário pode fazer do sistema. Dado que essas ações são interações realizadas pelos usuários, é comum a utilização de verbos no infinitivo para descrevê-las, o que torna a representação das funcionalidades mais clara e compreensível.

4) Comunicação (ou Ação): Esta categoria envolve ações específicas que um usuário ou ator realiza no contexto de um caso de uso, e pode ser observada na Figura 4. As ações podem ser classificadas em dois tipos distintos:

Inclusão: Quando um caso de uso requer que sua funcionalidade seja executada por meio de outro caso de uso. Em outras palavras, quando um caso de uso A inclui um caso de uso B, ao executar o caso de uso A, o caso de uso B é automaticamente acionado como parte do processo.
Notação no diagrama: <>

Extensão: O caso de uso atual opera normalmente, mas pode incluir etapas adicionais em caso de uso estendido. Isso significa que, se o caso de uso B estiver estendido pelo caso de uso A, ao executar o primeiro, o caso de uso B pode ou não ser ativado, dependendo das condições específicas.
Notação no diagrama: <<>>

## Casos de uso


## Historico de versões

| Versão | Data       | Descrição             | Autor              | Revisor             |
| ------ | ---------- | --------------------  | ------------------ | ------------------- |
| 1.0    | 24/10/2023 |Criação do Casos de uso| João Pedro         |                     |