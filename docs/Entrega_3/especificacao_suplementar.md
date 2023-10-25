# Especificação Suplementar

## Introdução 
O Detran Digital é um aplicativo móvel desenvolvido para proporcionar aos usuários um acesso fácil e conveniente a uma variedade de serviços relacionados a veículos e habilitação. Esta especificação suplementar estabelece os requisitos adicionais e as expectativas para o Detran Digital, com o objetivo de garantir a funcionalidade, segurança e usabilidade do aplicativo.

## Metodologia 
Para elaborar este documento, adotaremos uma versão adaptada do FURPS+. Nessa metodologia, os requisitos são divididos em categorias específicas: Funcionalidade (F), Usabilidade (U), Confiabilidade (R), Desempenho (P) e Suportabilidade (S). Além disso, incluímos requisitos não-funcionais como Design, Implementação e Interface.

## Funcionalidade
Os requisitos funcionais estão definidos por meio dos [Casos de uso](docs/Entrega_3/casos_de_uso.md).

## Usabilidade

_Tabela 1: Usabilidade_

| ID  | Descrição                                                                          |
|-----|------------------------------------------------------------------------------------|
|USA01|O sistema deve ter a interface do aplicativo deve ser intuitiva, garantindo que usuários de todas as idades possam interagir facilmente com o sistema.|
|USA02|O sistema deve oferecer orientações claras para os usuários durante todo o processo de renovação da carteira de motorista.|
|USA03|O sistema O aplicativo deve oferecer uma seção de ajuda com documentação clara e instruções detalhadas sobre como usar as diferentes funcionalidades, facilitando o entendimento para usuários com diferentes níveis de habilidade.|
|USA04|O sistema deve fornecer feedback claro e imediato para cada ação do usuário, indicando se uma ação foi bem-sucedida ou se há erros que precisam ser corrigidos.|
|USA05|Os usuários devem ter a opção de personalizar algumas configurações do aplicativo de acordo com suas preferências, como tamanho de fonte, tema de cores e notificações.|
|USA06|O sistema deve permitir a consulta de informações detalhadas sobre seus veículos, incluindo licenciamento e impostos.|

_Fonte: João Gabriel Elvas_

## Confiabilidade 

_Tabela 2: Confiabilidade_

| ID  | Descrição                                                                          |
|-----|------------------------------------------------------------------------------------|
|CON01|O sistema deve estar disponível 24/7, com tempo de inatividade mínimo para garantir que os usuários possam acessá-lo sempre que precisarem.|
|CON02|Todas as informações pessoais e transações dos usuários devem ser criptografadas e protegidas por medidas de segurança avançadas para evitar acessos não autorizados ou vazamentos de dado.|
|CON03|O sistema tem que garantir a confiablidade nas infirmações geradas, como numero de placa, boleto, quantidade de multas.|
|CON04|O sistema deve protejer dados sensiveis do usuário e do seu veículo.|
|CON05|Em caso de problemas ou manutenções programadas, o sistema deve comunicar de forma transparente aos usuários, fornecendo informações sobre a situação e estimativas de tempo para a resolução.|

_Fonte: João Gabriel Elvas_

## Desempenho 

_Tabela 3: Desempenho_

| ID  | Descrição                                                                          |
|-----|------------------------------------------------------------------------------------|
|DES01|O aplicativo deve apresentar tempos de resposta rápidos para todas as interações do usuário, garantindo uma experiência sem atrasos ou lentidões.|
|DES02|O sistema deve ser escalável para acomodar um aumento significativo no número de usuários, mantendo o desempenho mesmo durante picos de uso, como em períodos de vencimento de documentos.|
|DES03|O aplicativo deve ser otimizado para minimizar o consumo de recursos do dispositivo do usuário, como CPU e memória, para garantir que o desempenho global do dispositivo não seja prejudicado.|
|DES04|O sistema deve ser capaz de gerenciar eficientemente o tráfego de rede, evitando congestionamentos e garantindo que as transações sejam concluídas de forma suave, mesmo em redes com largura de banda limitada.|
|DES05|As consultas e transações realizadas pelos usuários devem ser processadas de maneira eficiente, utilizando recursos do sistema de forma otimizada para evitar sobrecargas.|

_Fonte: João Gabriel Elvas_

## Suportabilidade  

_Tabela 4: Suportabilidade_

| ID  | Descrição                                                                          |
|-----|------------------------------------------------------------------------------------|
|SUP01|O aplicativo deve ser facilmente atualizável para incluir novos recursos, correções de bugs e melhorias, com atualizações automáticas ou notificações claras para os usuários.|
|SUP02|O sistema deve ser projetado para facilitar testes extensivos, permitindo a detecção rápida de problemas e a implementação de soluções sem interromper o serviço.|
|SUP03|O código-fonte e a infraestrutura do aplicativo devem ser organizados de forma modular e bem documentada, facilitando a manutenção contínua e a incorporação de novas funcionalidades.|
|SUP04|O aplicativo deve ser projetado com uma arquitetura flexível que permita a fácil adição de novas funcionalidades e a integração com tecnologias emergentes no futuro.|
|SUP05|O aplicativo deve ser localizável para diferentes idiomas e regiões, adaptando-se automaticamente ao idioma e às preferências de formato de data, hora e moeda do usuário.|
|SUP06|Deve existir um sistema de suporte técnico eficaz, oferecendo canais claros para que os usuários relatem problemas e recebam assistência rápida e precisa quando necessário.|

_Fonte: João Gabriel Elvas_

## Design  

_Tabela 5: Design_

| ID  | Descrição                                                                          |
|-----|------------------------------------------------------------------------------------|
|DES01|O aplicativo deve seguir a paleta de cores definida.|
|DES02|O aplicativo deve utilizar ícones que representem bem sua funcionalidade.|
|DES03|O app deve ter um design bonito e familiar.|
|DES04|O design do aplicativo deve ser responsivo e otimizado para uma variedade de dispositivos móveis e sistemas operacionais.|

_Fonte: João Gabriel Elvas_

## Implementação  

_Tabela 6: Implementação_

| ID  | Descrição                                                                          |
|-----|------------------------------------------------------------------------------------|
|IMP01|O aplicativo deve ser compatível com os sistemas Android e IOS.|
|IMP02|O aplicativo deve ser facilmente atualizável para incluir novos recursos e correções de bugs conforme necessário.|

_Fonte: João Gabriel Elvas_

## Interface  

_Tabela 7: Interface_

| ID  | Descrição                                                                          |
|-----|------------------------------------------------------------------------------------|
|IMP01|A padronização da interface dos diversos componentes é essencial para evitar confusões por parte dos usuários. Todos os elementos devem seguir um padrão consistente, garantindo uma experiência de usuário coesa e intuitiva em todas as interações com o sistema.|
|IMP02|O sistema deve ser compatível com uma variedade de dispositivos móveis e sistemas operacionais para atingir um amplo público de usuários.|

## Referencias
* GAMBLE, S. Example: Supplementary Specification. [S. l.]: Pace University, 21 dez. 1998. Disponível em: https://csis.pace.edu/~marchese/SE616_New/Samples/Example%20%20Supplementary%20Specification.htm. Acesso em: 19 jul. 2022.'
* Samily Rocha Gois: Especificação Suplementar, 27 out. 2012. Disponível em: https://aprender3.unb.br/pluginfile.php/2124482/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf. Acesso em: 19 jul. 2022.'

## Versão
| Versão | Data       | Descrição             | Autor              | Revisor             |
| ------ | ---------- | --------------------  | ------------------ | ------------------- |
| 1.0    | 24/10/2023 |Criação documento      | João Gabriel Elvas | João Pedro          |
| 1.1    | 25/10/2023 |Legenda tabelas        | João Gabriel Elvas | João Pedro          |
