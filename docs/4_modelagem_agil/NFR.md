## 1. Introdução

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

## 2. Metodologia

Esse documento tem o objetivo ao utilizar o  NFR framework  documentar os requisitos nao funcionais do projeto, ou seja utilizar o SIG (Softgoal Interdependency Graph), um diagrama da propagação de impactos,  feito no [Draw io](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi38-7O4q2CAxWblJUCHQdoBtUQFnoECA0QAQ&url=https%3A%2F%2Fapp.diagrams.net%2F&usg=AOvVaw28S23h4_WI8toant9FYDpi&opi=89978449),e uma tabela de especificação, que possui informações sobre o NFR.

## 3. Legenda

Segue abaixo a legenda explicando os tipos de softgoal e os rotulos da propagação de impactos que serao utilizados.

![Legenda](https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-DETRAN/main/docs/assets/legenda.png)

<p align="center">
Figura 01 - Rotulos e representacoes das Softgoals<br>
(Fonte: João Pedro)
</p>

## 4. NFRs


### Usabilidade

Usabilidade (Usability) refere-se à facilidade de uso de um produto ou sistema. Suas cinco principais características incluem: facilidade de aprendizado (Learnability), eficiência de uso (Efficiency), memorabilidade (Memorability), satisfação do usuário (User Satisfaction) e tolerância a erros (Error Tolerance). Uma boa usabilidade visa tornar a interação dos usuários eficaz, eficiente, satisfatória, fácil de aprender (Learnability) e capaz de lidar com erros (Error Tolerance). Esses aspectos são cruciais para garantir uma experiência positiva e produtiva para os usuários.

**SIG  (SIG – Softgoal Interdependency Graph):**

![Sig Usability](https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-DETRAN/main/docs/assets/sig-usabilidade.png)

<p align="center">
Figura 02- SIG:Usabilidade<br>
(Fonte: João Pedro)
</p>

**Propagação:**

![prop Usability](https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-DETRAN/main/docs/assets/propagacao_usability.png)

<p align="center">
Figura 03- Propagação:Usabilidade<br>
(Fonte: João Pedro)
</p>

### Confiabilidade

A Confiabilidade é um aspecto fundamental para garantir que o aplicativo Detran digital atenda efetivamente às necessidades de seus usuários:

1. **Confiança do usuário**: Se o aplicativo for confiável, os usuários terão mais confiança em usá-lo para realizar tarefas importantes. Isso pode levar a um aumento na adoção do aplicativo.
2. **Precisão das informações**: Como o aplicativo lida com informações sensíveis e importantes, é crucial que ele seja confiável para garantir que as informações sejam precisas e atualizadas.
3. **Disponibilidade**: O aplicativo precisa estar disponível sempre que os usuários precisarem dele. Se o aplicativo não for confiável e estiver frequentemente indisponível ou falhando, isso pode causar frustração e inconveniência para os usuários.
4. **Segurança dos dados**: A confiabilidade também está relacionada à segurança dos dados. Se o aplicativo for confiável, os usuários podem confiar que seus dados estão seguros e protegidos contra corrupção ou perda.
5. **Manutenção e atualizações**: Um aplicativo confiável é mais fácil de manter e atualizar. Isso significa que novos recursos podem ser adicionados mais facilmente e os bugs podem ser corrigidos de maneira mais eficiente.


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



### Desempenho

Desempenho em uma aplicação refere-se à sua capacidade de executar tarefas de forma eficiente. Duas características-chave do desempenho são o tempo de resposta ágil e o baixo uso de memória. Um tempo de resposta rápido garante que a aplicação seja responsiva, enquanto o uso eficiente de memória otimiza o uso dos recursos do sistema, proporcionando uma experiência mais suave e eficaz aos usuários.

**SIG  (SIG – Softgoal Interdependency Graph):**

![Sig desempenho](https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-DETRAN/main/docs/assets/sig_desempenho.png)

<p align="center">
Figura 06- SIG:Desempenho<br>
(Fonte: João Pedro)
</p>

**Propagação:**

![prop desempenho](https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-DETRAN/main/docs/assets/prop_desempenho.png)

<p align="center">
Figura 07- Propagação:Desempenho<br>
(Fonte: João Pedro)
</p>

### Suportabilidade
Garanti  que o aplicativo Detran digital seja suportável e eficaz para os usuários:


1. **Desempenho**: Este subnó garante que o aplicativo funcione de maneira eficiente e rápida. Isso inclui:
    - **Eficiência**: O aplicativo deve usar recursos de maneira eficiente para garantir um bom desempenho.
    - **Alta performance**: O aplicativo deve ser capaz de lidar com altas cargas de trabalho e ainda manter um bom desempenho.

2. **Segurança**: Este subnó garante que os dados no aplicativo sejam seguros e protegidos. Isso inclui:
    - **Proteção de dados**: O aplicativo deve ter mecanismos para proteger os dados dos usuários de acessos não autorizados.
    - **Autenticação segura**: O aplicativo deve ter um sistema de autenticação seguro para garantir que apenas usuários autorizados tenham acesso.

3. **Compatibilidade**: Este subnó garante que o aplicativo possa funcionar em diferentes dispositivos e sistemas operacionais. Isso inclui:
    - **Suporte a múltiplos dispositivos**: O aplicativo deve ser compatível com uma variedade de dispositivos, como smartphones, tablets e computadores.
    - **Suporte a múltiplos sistemas operacionais**: O aplicativo deve ser capaz de funcionar em diferentes sistemas operacionais, como Android, iOS, Windows, etc.

4. **Robustez**: Este subnó garante que o aplicativo possa lidar com falhas e erros de maneira eficaz. Isso inclui:
    - **Tolerância a falhas de rede**: O aplicativo deve ser capaz de lidar com falhas de rede e ainda funcionar corretamente.
    - **Recuperação de erros**: Se ocorrerem erros, o aplicativo deve ser capaz de se recuperar e continuar funcionando.


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




## 5. Conclusão

Com base no documento feito,pode-se concluir a partir do softgoals que a maioria  das características estudadas atendeu os requisitos não funcionais propostos porem muitos ficaram incompletos o que se faz necessários melhorias.

## Bibliografia
> [1] Chung, Lawrence; A. Nixon, Brian; Mylopoulos, John. Non-Functional Requirements in Software Engineering. Acesso em 26 de Dezembro de 2022

> [2] SILVA, R. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Tese (Mestrado em Engenharia de Software) - Centro de Informática, Universidade Federal de Pernambuco. Recife, p. 155. 2019. Acesso em: 25 de Dezembro de 2022

## Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0 | 06/11/2023 | Criação do documento |  e Guilherme | João Gabriel |
| 1.0 | 06/12/2023 | Padronização | João Gabriel | João Pedro |
