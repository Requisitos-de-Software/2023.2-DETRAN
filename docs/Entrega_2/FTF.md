# First Thing First

## Introdução


A abordagem "First Things First" em requisitos refere-se a uma estratégia de priorização no processo de desenvolvimento de software e gestão de requisitos. Essa abordagem enfatiza a importância de identificar e abordar primeiro os requisitos mais críticos e essenciais de um projeto, antes de lidar com requisitos menos importantes.

Passo 1: Liste todos os requisitos, funcionalidades ou casos de uso que você deseja priorizar em uma planilha. Certifique-se de que todos os itens estejam no mesmo nível de abstração, ou seja, não misture requisitos individuais com funcionalidades do produto. Se certas funcionalidades estiverem logicamente relacionadas, inclua apenas a funcionalidade principal na análise. Se você tiver mais itens do que o gerenciável, agrupe funcionalidades relacionadas para criar uma lista inicial mais gerenciável. Você pode fazer uma segunda análise em um nível mais detalhado de requisitos, se necessário.

Passo 2: Estime o benefício relativo que cada funcionalidade oferece ao cliente ou ao negócio em uma escala de 1 a 9, onde 1 indica muito pouco benefício e 9 é o benefício máximo possível. Esses benefícios indicam a adequação aos requisitos de negócios do produto. Seus representantes de clientes são as melhores pessoas para julgar esses benefícios.

Passo 3: Estime a penalidade relativa que o cliente ou o negócio sofreria se a funcionalidade não fosse incluída, usando novamente uma escala de 1 a 9, onde 1 significa essencialmente nenhuma penalidade e 9 indica uma desvantagem muito séria. Por exemplo, não cumprir uma regulamentação governamental pode incorrer em uma penalidade alta, mesmo que o benefício para o cliente seja baixo. Requisitos que têm tanto baixo benefício quanto baixa penalidade adicionam custo, mas pouco valor; eles podem ser casos de "gold plating" (adicionar recursos sem necessidade).

Passo 4: A coluna de "Valor Total" é a soma do benefício relativo e da penalidade relativa. Por padrão, benefício e penalidade têm o mesmo peso. Você pode ajustar os pesos desses dois fatores. A planilha totaliza os valores das funcionalidades e calcula a porcentagem do valor total do produto que é atribuída a cada funcionalidade.

Passo 5: Estime o custo relativo de implementação de cada funcionalidade, novamente em uma escala de 1 a 9. A planilha calculará a porcentagem do custo total para cada funcionalidade. Os desenvolvedores estimam as classificações de custo com base em fatores como complexidade do requisito, trabalho na interface do usuário, potencial para reutilização de designs ou código existentes e níveis de teste e documentação necessários.

Passo 6: Os desenvolvedores estimam o grau relativo de risco técnico ou outro risco associado a cada funcionalidade em uma escala de 1 a 9. Uma estimativa de 1 significa que você pode programar isso sem dificuldades, enquanto 9 indica preocupações sérias com a viabilidade, disponibilidade de pessoal com a experiência necessária ou o uso de ferramentas e tecnologias não comprovadas ou desconhecidas. A planilha calculará a porcentagem do risco total que vem de cada funcionalidade.

Por padrão, custo e risco têm o mesmo peso e cada um tem o mesmo peso que os termos de benefício e penalidade. Você pode ajustar os pesos de custo e risco na planilha.

Passo 7: Depois de inserir as estimativas na planilha, ela calculará um número de prioridade para cada funcionalidade. A fórmula para a coluna de Prioridade é: prioridade = valor % / (custo % * peso do custo + risco % * peso do risco).

Passo 8: Ordene a lista de funcionalidades em ordem decrescente de prioridade calculada. As funcionalidades no topo da lista têm o equilíbrio mais favorável entre valor, custo e risco e, portanto, devem ter prioridade mais alta na implementação. Os representantes-chave de clientes e desenvolvedores devem revisar a planilha concluída para concordar com as classificações e a sequência resultante.



## Detran

A seguir se encontra a *tabela 1*  com a tabela levantada pela equipe para o aplicativo Detran




| Funcionalidade                     | Benefício Relativo | Penalidade Relativa | Valor Total | Valor Total % | Custo Relativo | Custo Relativo % | Risco Relativo | Risco Relativo % | Prioridade | Requisitos                      |
|------------------------------------|--------------------|----------------------|-------------|---------------|----------------|------------------|----------------|------------------|------------|---------------------------------|
| CNH digital                        | 9                  | 9                    | 18          | 14.76%        | 3              | 6.98%            | 2              | 5.13%            | 1.636       | ADD3, ADD6, ST11                |
| CRLV digital                       | 8                  | 9                    | 17          | 13.84%        | 4              | 9.30%            | 4              | 10.26%           | 0.860       | ADD12, ST13, PE01, PE03, ST12   |
| Vencimento da CNH                  | 6                  | 6                    | 12          | 9.84%         | 6              | 13.95%           | 5              | 17.95%           | 0.705       | ADD3, ST11                      |
| Gerenciamento de infrações e multas | 7                  | 8                    | 15          | 12.3%         | 8              | 18.60%           | 7              | 20.51%           | 0.660       | PE04, PE05, ST02, ST03, ST12, ADD4 |
| Indicação de principal condutor    | 5                  | 4                    | 9           | 7.38%         | 9              | 20.93%           | 9              | 23.08%           | 0.238       | ADD7                            |
| Notificação de recall              | 3                  | 2                    | 5           | 4.1%          | 4              | 9.30%            | 4              | 12.82%           | 0.222       | ADD11                           |
| Histórico de emissão da CNH        | 3                  | 3                    | 6           | 4.92%         | 9              | 20.93%           | 8              | 23.08%           | 0.195       | ADD12, ST11                     |
| Segurança de Dados                 | 5                  | 4                    | 9           | 7.38%         | 7              | 16.28%           | 8              | 23.08%           | 0.238       | ADD8, ST17                      |
| Total                              | 46                 | 45                   | 91          | 100%          | 48             | 100%             | 39             | 100%             | 5.420       | -                               |

Fonte:Autores



A *Tabela 2* abaixo indica a legenda dos codigos dos requisitos:

*Tabela 2*

| Número do Requisito | Categoria              | Requisito                                                     |
|---------------------|------------------------|-------------------------------------------------------------|
| ADD1                | RF                     | Baixar o aplicativo em sistemas Android (versão 5 ou superior) e iOS.           |
| ADD2                | RF                     | Permitir cadastrro no Portal de Serviços, exigindo um endereço de e-mail válido.   |
| ADD3                | RF                     | Oferecer opção de alteração de senha no aplicativo.       |
| ADD4                | RF                     | Disponibilizar variedade de serviços relacionados à CNH e veículos.               |
| ADD5                | RNF                    | Garantir compatibilidade com Android 5 ou superior.        |
| ADD6                | RNF                    | Assegurar compatibilidade com iOS.                          |
| ADD7                | RI                     | Projetar interface fácil de usar para cadaAstro no Portal de Serviços.             |
| ADD8                | RI                     | Criar interface para alteração de senha de forma intuitiva e segura.              |
| ADD9                | RI                     | Apresentar opções de serviço de forma clara e acessível aos usuários.            |
| ADD10               | RPR                    | Garantir desempenho aceitável em dispositivos Android e iOS.                        |
| ADD11               | RR                     | Risco associado à segurança da alteração de senha e envio de e-mails.             |
| ADD12               | RT                     | Realizar testes para validação de funcionalidades do aplicativo.                  |
| ADD13               | RF                     | Deve ser possível baixar os boletos com os débitos do meu veículo.               |
| ADD14               | RF                     | Deve ser possível realizar o pagamento dos boletos com os débitos do meu veículo.|
| ADD15               | RF                     | Deve ser possível baixar os documentos do meu veículo.    |
| ADD16               | RF                     | Deve ser possível consultar os dados de veículos a partir do renavam.             |
| ADD17               | RF                     | Deve ser possível consultar os dados de veículos a partir da placa.              |
| ADD18               | RF                     | Deve ser possível baixar a minha CNH digital.             |
| ADD19               | RF                     | Deve ser possível realizar a transferência de veículo.    |
| ADD20               | RNF                    | O aplicativo deverá guardar as informações de login do usuário.                   |
| ADD21                | RF                     | Receber notificações automáticas sobre a proximidade da expiração da carteira de motorista. | 
| ADD22                | RF                     | Consultar multas associadas ao veículo de forma rápida e precisa. | 
| ADD23                | RF                     | Pagar multas de trânsito online, utilizando diferentes métodos de pagamento. | 
| ADD24                | RF                     | Verificar informações do veículo, incluindo licenciamento e impostos, de forma fácil e conveniente. | 
| ADD25                | RF                     | Receber dicas de segurança personalizadas para o veículo, baseadas nas condições de viagem. | 
| ADD26                | RF                     | Receber notificações em tempo real sobre atualizações nas leis de trânsito e outras informações relevantes. | 
| ADD27                | RF                     | Agendar atendimento presencial no Detran para evitar filas e garantir eficiência no atendimento. | 
| ADD28                | RF                     | Alterar o endereço associado à CNH sem a necessidade de ir pessoalmente a um posto do Detran. | 
| ADD29                | RF                     | Alterar o endereço associado ao veículo sem a necessidade de ir pessoalmente a um posto do Detran. | 
| ADD30                | RF                     | Solicitar autorização de estacionamento para idoso por meio do aplicativo. | 
| ADD31                | RF                     | Consultar a CNH para verificar sua validade, categoria e pontos de penalidade. | 
| ADD32                | RF                     | Consultar informações detalhadas sobre veículos, incluindo hiAstórico de proprietários, débitos pendentes e informações do veículo. | 
| ADD33                | RF                     | Emitir o CRLV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) de forma rápida e fácil, sem precisar ir pessoalmente ao Detran. | 
| ADD34                | RF                     | Solicitar a recolocação de placa em caso de perda, roubo ou dano irreparável pelo aplicativo. | 


fonte:Autores
## Referências
> First Things First: Prioritizing Requirements. E.Wiegers, Karl. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf Acesso em 02 de Outubro de 2023. 

# Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0    | 30/09/2023 | Adicionado tabela e introduçã0 | Guilherme Nishimura |João Pedro |
| 1.2    | 03/10/2023 | Adicionando a tabela aos requisitos  | Guilherme Nishimura |João Pedro |
