## Introdução

O NFR (Non-Functional Requirements) Framework de Requisitos Não Funcionais, é uma abordagem sistêmica e estruturada para lidar com os requisitos que não se relacionam diretamente com as funcionalidades de um sistema de software, mas sim com as suas características de desempenho, segurança, usabilidade, confiabilidade e outros atributos que não são funcionalidades específicas. Os requisitos não funcionais desempenham um papel fundamental no desenvolvimento de software, uma vez que afetam a qualidade geral do sistema e a experiência do usuário.

Fornecendo um conjunto de diretrizes, práticas e técnicas para capturar, analisar, especificar e gerenciar esses requisitos não funcionais de forma eficaz. Ele ajuda a entender melhor as expectativas dos stakeholders em relação a aspectos como desempenho, segurança, escalabilidade, usabilidade e outros critérios de qualidade, permitindo que se integre esses requisitos na arquitetura e no design do software.

O objetivo principal do framework é fornecer uma estrutura de representação para documentar o planejamento e o raciocínio por trás do processo de definição de requisitos, utilizando diagramas denominados Gráficos de Interdependência de Softgoals (SIGs).

Os "softgoals" são conceitos abstratos que se desejam considerar durante a análise, a fim de determinar se eles serão ou não atendidos, ou seja, se serão escolhidos para serem implementados ou não.

Esses "softgoals" podem ser categorizados em três tipos distintos:

- 1)"Softgoals NFR" representam os Requisitos Não Funcionais (NFR) e podem estar relacionados entre si. Eles são organizados em catálogos e são apresentados de forma hierárquica durante o desenvolvimento do projeto.
</br>
- 2)"Softgoals de Operacionalização" representam as soluções de implementação para satisfazer os "softgoals NFR" ou outros "softgoals de operacionalização". Essas soluções englobam operações, processos, representações de dados, estruturações e restrições no sistema alvo, com o propósito de atender às necessidades indicadas pelos "softgoals NFR" e "softgoals de operacionalização".
</br>
- 3)"Softgoals de Afirmação" possibilitam a consideração e reflexão das características do domínio, como prioridades e carga de trabalho, no processo de tomada de decisões.

## Metodologia

Esse documento tem o objetivo ao utilizar o  NFR framework  documentar os requisitos nao funcionais do projeto, ou seja utilizar o SIG (Softgoal Interdependency Graph), um diagrama da propagação de impactos,  feito no [Draw io](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi38-7O4q2CAxWblJUCHQdoBtUQFnoECA0QAQ&url=https%3A%2F%2Fapp.diagrams.net%2F&usg=AOvVaw28S23h4_WI8toant9FYDpi&opi=89978449),e uma tabela de especificação, que possui informações sobre o NFR.

## Legenda

Segue abaixo a legenda explicando os tipos de softgoal e os rotulos da propagação de impactos que serao utilizados.

![](/docs/assets/legenda.png)

<p align="center">
Figura 01 - Rotulos e representacoes das Softgoals<br>
(Fonte: João Pedro)
</p>

## NFRs


### Usabilidade

**SIG  (SIG – Softgoal Interdependency Graph):**

![Sig Usability](/docs/assets/sig-usabilidade.png)

<p align="center">
Figura 02- SIG:Usabilidade<br>
(Fonte: João Pedro)
</p>

**Propagação:**

![prop Usability](/docs/assets/propagacao_usability.png)

<p align="center">
Figura 03- Propagação:Usabilidade<br>
(Fonte: João Pedro)
</p>

### Confiabilidade

![Deinifitivo 2 drawio](https://github.com/Requisitos-de-Software/2023.2-DETRAN/assets/78215376/bf2d4c1c-b76d-4ccd-8da5-663fb9b5ffbb)

<p align="center">
Figura 04- SIG:Confiabilidade<br>
(Fonte: Guilherme Nishimura)
</p>

**Propagação:**
![Definitivo drawio](https://github.com/Requisitos-de-Software/2023.2-DETRAN/assets/78215376/af22fe17-06c8-4703-a89b-ee142b6f00b9)

<p align="center">
Figura 05- Propagação:Confiabilidade<br>
(Fonte: Guilherme Nishimura)
</p>

### Desempenho

**SIG  (SIG – Softgoal Interdependency Graph):**

![Sig desempenho](/docs/assets/sig_desempenho.png)

<p align="center">
Figura 06- SIG:Desempenho<br>
(Fonte: João Pedro)
</p>

**Propagação:**

![prop desempenho](/docs/assets/prop_desempenho.png)

<p align="center">
Figura 07- Propagação:Desempenho<br>
(Fonte: João Pedro)
</p>

### Suportabilidade

![Definitivo 3 drawio](https://github.com/Requisitos-de-Software/2023.2-DETRAN/assets/78215376/c2ba4b8b-7374-4501-a15c-a9f83310a3b3)

<p align="center">
Figura 08- SIG:Suportabilidade<br>
(Fonte: Guilherme Nishimura)
</p>

**Propagação:**
![dEFINICITO 5 drawio](https://github.com/Requisitos-de-Software/2023.2-DETRAN/assets/78215376/8ed4426f-de7a-4142-8b97-4882045f339c)

<p align="center">
Figura 09- Propagação:Suportabilidade<br>
(Fonte: Guilherme Nishimura)
</p>

## Conclusão
## Referências
[1] Chung, Lawrence; A. Nixon, Brian; Mylopoulos, John. Non-Functional Requirements in Software Engineering. Acesso em 26 de Dezembro de 2022

[2] SILVA, R. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Tese (Mestrado em Engenharia de Software) - Centro de Informática, Universidade Federal de Pernambuco. Recife, p. 155. 2019. Acesso em: 25 de Dezembro de 2022

## Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0 | 06/11/2023 | Criação do documento | João Pedro e Guilherme | - |
| 1.1 | 06/11/2023 | Adição de tabelas | João Pedro e Guilherme | - |
