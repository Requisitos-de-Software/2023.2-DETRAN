# Léxico

## 1. Introdução
Léxico é um conjunto de termos, palavras e símbolos que são usados para descrever um sistema ou software. Esses termos são escolhidos para serem precisos e não ambíguos, para que todos os envolvidos no projeto possam entender o que está sendo discutido.

## 2. Metodologia
Foi criada uma tabela semelhante à *tabela 1* abaixo para facilitar a compreensão desses termos com base nos requisitos já elicitados pelo grupo em [Requisitos Elicitados](https://github.com/Requisitos-de-Software/2023.2-DETRAN/blob/main/docs/Entrega_2/requisitos_elicitados.md).

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Nome que o léxico irá possuir | Sinônimo do léxico | Noção do léxico | Impacto do léxico | Classificação em Objeto, Verbo ou Estado | ID dos requisitos |

<p align="center">
Tabela 01 - Modelo de tabela<br>
(Fonte: Guilherme Nishimura)
</p>

## 3. Léxicos Gerados

A seguir, com base na *tabela 1* acima, foram gerados pela equipe os léxicos:

### L1: Usuario

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Usuario | Cliente | Pessoa que ira utilizar o aplicativo | Usuario que que possui CNH ou deseja verificar situação do veiculo que é a pessoa ativa que irá utilizar o aplicativo Detran .| Objeto | ADD1, ADD2, ADD3, ADD4, ADD5, ADD6, ADD7, ADD8, ADD9, ADD10, ADD11, ADD12 |

<p align="center">
Tabela 02 - Léxico Usuario<br>
(Fonte: Guilherme Nishimura)
</p>

### L2: CNH

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| CNH | Carteira Nacional de Habilitação, carteira de motorista, habilitação | Documento que comprova que o usuário está apto a dirigir veículos de determinada categoria | A CNH é um documento obrigatório para os condutores de veículos e deve estar sempre atualizada e válida. O aplicativo deve permitir ao usuário consultar, baixar e alterar os dados da sua CNH | Objeto | ADD18, ADD21, ADD28, ADD31 |

<p align="center">
Tabela 03 - Léxico CNH<br>
(Fonte: Guilherme Nishimura)
</p>

### L3: Veículo

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Veículo | Carro, moto, caminhão, automóvel | Meio de transporte que possui um motor e rodas, e que é registrado e licenciado pelo Detran | O veículo é um bem do usuário sujeito a impostos, multas e outras obrigações legais. O aplicativo deve permitir ao usuário consultar, baixar e alterar os dados do seu veículo, bem como realizar pagamentos e transferências relacionados ao mesmo | Objeto | ADD13, ADD14, ADD15, ADD16, ADD17, ADD19, ADD20, ADD22, ADD23, ADD24, ADD25, ADD26, ADD27, ADD29, ADD30, ADD32, ADD33 |

<p align="center">
Tabela 04 - Léxico Veículo<br>
(Fonte: Guilherme Nishimura)
</p>

### L4: Portal de Serviços

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Portal de Serviços | Portal do Detran, site do Detran | Página na internet que permite ao usuário acessar os serviços do Detran pelo computador ou navegador web | O portal de serviços é uma alternativa ao aplicativo para os usuários que preferem usar o computador ou não possuem um dispositivo compatível com o app. O portal deve oferecer as mesmas funcionalidades do aplicativo de forma fácil e conveniente | Objeto | Todos os requisitos |

<p align="center">
Tabela 05 - Léxico Portal de Serviços<br>
(Fonte: Guilherme Nishimura)
</p>

### L5: Baixar

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Baixar | Download, transferir | Ação de copiar um arquivo ou documento da internet para o dispositivo do usuário | Baixar um arquivo ou documento permite ao usuário visualizá-lo offline ou imprimi-lo. O aplicativo deve permitir ao usuário baixar os boletos com os débitos do seu veículo, os documentos do seu veículo e a sua CNH digital | Verbo | ADD1, ADD13, ADD15, ADD18 |

<p align="center">
Tabela 06 - Léxico Baixar<br>
(Fonte: Guilherme Nishimura)
</p>

### L6: Pagar

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Pagar | Quitar, liquidar | Ação de efetuar o pagamento de um valor devido por um serviço ou produto | Pagar um valor devido permite ao usuário regularizar sua situação perante o Detran e evitar penalidades. O aplicativo deve permitir ao usuário pagar os boletos com os débitos do seu veículo e as multas de trânsito online | Verbo | ADD14, ADD23 |

<p align="center">
Tabela 07 - Léxico Pagar<br>
(Fonte: Guilherme Nishimura)
</p>

### L7: Consultar

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Consultar | Verificar, checar, pesquisar, buscar | Ação de obter informações sobre um determinado assunto ou objeto | Consultar informações permite ao usuário se informar sobre sua situação perante o Detran e tomar decisões mais conscientes. O aplicativo deve permitir ao usuário consultar os dados de veículos a partir do renavam ou da placa, as multas associadas ao veículo, as informações do veículo, a CNH e as informações detalhadas sobre veículos | Verbo | ADD16, ADD17, ADD22, ADD24, ADD31, ADD32 |

<p align="center">
Tabela 08 - Léxico Consultar<br>
(Fonte: Guilherme Nishimura)
</p>

### L8: Alterar

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Alterar | Modificar, mudar, atualizar | Ação de modificar ou atualizar os dados ou informações de um objeto ou assunto | Alterar dados ou informações permite ao usuário manter sua situação perante o Detran atualizada e evitar problemas futuros. O aplicativo deve permitir ao usuário alterar a senha no aplicativo, o endereço associado à CNH e o endereço associado ao veículo | Verbo | ADD3, ADD28, ADD29 |

<p align="center">
Tabela 09 - Léxico Alterar<br>
(Fonte: Guilherme Nishimura)
</p>

### L9: Receber

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Receber | Obter, ganhar, adquirir | Ação de ter acesso a algo que foi enviado ou disponibilizado por outra parte | Receber algo permite ao usuário se beneficiar de um serviço ou produto que foi oferecido ou solicitado. O aplicativo deve permitir ao usuário receber notificações automáticas sobre a proximidade da expiração da carteira de motorista, notificações em tempo real sobre atualizações nas leis de trânsito e outras informações relevantes, e dicas de segurança personalizadas para o veículo | Verbo | ADD21, ADD25, ADD26 |

<p align="center">
Tabela 10 - Léxico Receber<br>
(Fonte: Guilherme Nishimura)
</p>

### L10: Agendar

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Agendar | Marcar, reservar, programar | Ação de definir uma data e horário para um atendimento ou serviço | Agendar um atendimento ou serviço permite ao usuário garantir sua vaga e evitar filas e esperas desnecessárias. O aplicativo deve permitir ao usuário agendar atendimento presencial no Detran para resolver questões que não podem ser feitas pelo app | Verbo | ADD27 |

<p align="center">
Tabela 11 - Léxico Agendar<br>
(Fonte: Guilherme Nishimura)
</p>

### L11: Solicitar

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Solicitar | Pedir, requerer, demandar | Ação de expressar o desejo ou a necessidade de algo que deve ser providenciado por outra parte | Solicitar algo permite ao usuário obter um benefício ou direito que lhe é garantido por lei ou por contrato. O aplicativo deve permitir ao usuário solicitar autorização de estacionamento para idoso, a recolocação de placa em caso de perda, roubo ou dano irreparável, e a transferência de veículo | Verbo | ADD19, ADD30, ADD34 |

<p align="center">
Tabela 12 - Léxico Solicitar<br>
(Fonte: Guilherme Nishimura)
</p>

### L12: Emitir

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Emitir | Gerar, produzir, criar | Ação de criar ou disponibilizar um documento ou certificado que comprova uma situação ou condição | Emitir um documento ou certificado permite ao usuário comprovar sua situação ou condição perante o Detran e outras entidades. O aplicativo deve permitir ao usuário emitir o CRLV-e (Certificado de Registro e Licenciamento de Veículo eletrônico) de forma rápida e fácil | Verbo | ADD33 |

<p align="center">
Tabela 13 - Léxico Emitir<br>
(Fonte: Guilherme Nishimura)
</p>

### L13: Válido

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Válido | Valido, vigente, legal | Qualidade de algo que está dentro do prazo de validade, que é reconhecido como legítimo e que tem efeito jurídico | Algo válido tem valor e credibilidade perante as autoridades e a sociedade e pode ser usado para comprovar uma situação ou condição. O aplicativo deve exigir um endereço de e-mail válido para o cadastro no Portal de Serviços e deve permitir ao usuário consultar a validade da sua CNH | Estado | ADD2, ADD31 |

<p align="center">
Tabela 14 - Léxico Válido<br>
(Fonte: Guilherme Nishimura)
</p>

### L14: Compatível

| Léxico | Sinônimo | Noção | Impacto | Classificação | ID dos requisitos |
| --- | --- | --- | --- | --- | --- |
| Compatível | Compativel, adaptável, ajustável | Qualidade de algo que pode funcionar ou se adequar a outro elemento sem conflitos ou problemas | Algo compatível tem maior alcance e versatilidade e pode atender às necessidades e preferências de diferentes usuários. O aplicativo deve garantir compatibilidade com Android 5 ou superior e iOS e deve ter uma interface fácil de usar para cadastrar no Portal de Serviços | Estado | ADD1, ADD5, ADD6, ADD7 |

<p align="center">
Tabela 15 - Léxico Compatível<br>
(Fonte: Guilherme Nishimura)
</p>

### L15: E-mail

| Campo | Sinônimos | Descrição | Observações | Tipo | Campos Relacionados |
| --- | --- | --- | --- | --- | --- |
| L5: E-mail | Correio eletrônico, mensagem eletrônica, email | Comunicação escrita que é enviada ou recebida por meio de um serviço online | O e-mail é um meio de comunicação entre o usuário e o Detran e deve ser usado para confirmar o cadastro no Portal de Serviços, enviar a senha do aplicativo e outras informações relevantes | Objeto | ADD2, ADD3, ADD11 |

<p align="center">
Tabela 16 - Léxico E-mail<br>
(Fonte: Guilherme Nishimura)
</p>

### L16: Multa

| Campo | Sinônimos | Descrição | Observações | Tipo | Campos Relacionados |
| --- | --- | --- | --- | --- | --- |
| L6: Multa | Penalidade, infração, sanção | Valor que deve ser pago pelo usuário por cometer uma irregularidade no trânsito, como excesso de velocidade, estacionamento proibido ou dirigir sem CNH | A multa é uma consequência negativa para o usuário que desrespeita as leis de trânsito e deve ser paga para evitar maiores problemas. O aplicativo deve permitir ao usuário consultar e pagar as multas associadas ao seu veículo online | Objeto | ADD22, ADD23 |

<p align="center">
Tabela 17 - Léxico Multa<br>
(Fonte: Guilherme Nishimura)
</p>

### L17: Expirado

| Campo | Sinônimos | Descrição | Observações | Tipo | Campos Relacionados |
| --- | --- | --- | --- | --- | --- |
| L7: Expirado | Vencido, ultrapassado, caducado | Qualidade de algo que está fora do prazo de validade, que não é mais reconhecido como legítimo e que perdeu o efeito jurídico | Algo expirado não tem mais valor ou credibilidade perante as autoridades e a sociedade e não pode ser usado para comprovar uma situação ou condição. O aplicativo deve permitir ao usuário receber notificações automáticas sobre a proximidade da expiração da sua CNH e deve impedir o usuário de baixar a sua CNH digital se ela estiver expirada | Estado | ADD18, ADD21 |

<p align="center">
Tabela 18 - Léxico Expirado<br>
(Fonte: Guilherme Nishimura)
</p>

## Bibliografia

> Slides disponibilizados pelo professor da disciplina, “Modelagem parte 1, Requisitos - Aula 10” - Milene Serrano. Acesso em: 22 Out. 2023.

## Histórico de versão

| Versão | Data       | Descrição            | Autor              | Revisor             |
| ------ | ---------- | -------------------- | ------------------ | ------------------- |
| 1.0    | 24/10/2023 | Criação do documento | Guilherme Nishimura | Vitor, Pedro |
| 2.0 | 04/11/2023 | Padronização | Vitor Borges | Pedro |
