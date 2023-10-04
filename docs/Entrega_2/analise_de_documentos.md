# Análise de documentos

## Introdução

Este documento tem o objetivo de a partir dos documentos disponibilizados pelo detran digital elicitar e documentar os requisitos de software parado aplicativo, no qual sera utilizada a técnica de análise de documentos. O Detran Digitalvisa modernizar e digitalizar os serviços oferecidos pelos Departamentos de Trânsito (Detran) em diversos estados e países atraves  de serviços relacionados a veículos e habilitação.

## Técnica Utilizada

A técnica ao qual sera utilizada e a análise de documentos. Sendo particularmente útil quando os requisitos do software estão implícitos em documentos existentes e podendo ser extraídos por meio de uma análise cuidadosa do conteúdo. Desse modo vale ressaltar que e uma técnica complementar a outras técnicas de elicitação de requisitos, como entrevistas e questionarios, dentre outras

# Elicitação de requisitos do Detran Digital

Vale ressaltar que a pagina de documentos utilizada para a elicitação com base na analise de documentos foi a seguinte: https://www.detran.df.gov.br/passo-a-passo-para-os-servicos-do-detran/
## Funcionalidades e Recursos:

- Baixar o aplicativo para sistemas Android (versão 5 ou superior) e iOS:
    - Garantir que o aplicativo seja disponível para download e funcionamento em dispositivos Android com versão 5 ou superior, bem como em dispositivos iOS.

- Cadastro no Portal de Serviços:
    - Permitir que os usuários se cadastrem no Portal de Serviços, fornecendo informações necessárias e um endereço de e-mail válido para acesso às funcionalidades.

- Alterar senha no aplicativo:
    - Oferecer aos usuários a opção de alterar a senha no aplicativo, fornecendo um processo seguro e fácil para redefinir a senha de acesso.

- Acesso a uma variedade de serviços relacionados à CNH e veículos:
    - Disponibilizar um conjunto de serviços no aplicativo, incluindo alteração de endereço da CNH e do veículo, consulta de informações, emissão de documentos, entre outros.

## Requisitos Técnicos:

- Compatibilidade com Android 5 ou superior:
    - Certificar que o aplicativo é funcional em dispositivos com Android 5 ou versões mais recentes, atendendo aos requisitos de compatibilidade dessa plataforma.

- Compatibilidade com iOS:
    - Assegurar que o aplicativo seja compatível e funcional em dispositivos iOS, cumprindo os padrões e requisitos técnicos da plataforma.

## Requisitos de Usabilidade e Acessibilidade:

- Facilidade de cadastro no Portal de Serviços com um endereço de e-mail válido:
    - Projetar um processo de cadastro intuitivo e simples, facilitando o registro no Portal de Serviços utilizando um endereço de e-mail válido.

- Opção de alteração de senha no aplicativo para melhor usabilidade e segurança:
    - Criar uma interface fácil de usar que permita aos usuários alterar suas senhas de forma intuitiva e que promova a segurança das contas.

- Disponibilização de opções de serviço de forma clara e acessível aos usuários:
    - Apresentar os serviços disponíveis de maneira clara e acessível, facilitando a compreensão e navegação para os usuários.

## Requisitos de Desempenho e Escalabilidade:

- Desempenho aceitável em dispositivos com Android 5 ou superior, bem como em dispositivos iOS:
    Garantir que o aplicativo funcione de forma eficiente e responsiva em uma variedade de dispositivos, proporcionando uma boa experiência de usuário.

## Requisitos de Segurança e Privacidade:

- Opção para o usuário alterar a senha e reenviar e-mail de validação:
    - Implementar uma funcionalidade segura que permita aos usuários alterar suas senhas e, se necessário, reenviar e-mails de validação para manter a segurança das contas.

- Garantir que a alteração de senha seja feita de forma segura e que o e-mail de validação seja enviado de forma segura para garantir a privacidade do usuário:
    - Adotar práticas de segurança robustas para proteger as informações dos usuários durante o processo de alteração de senha e envio de e-mails de validação, respeitando a privacidade dos usuários.

## Tabela de requisitos
A tabela 1 disposta abaixo representa todos os requisitos levantados durante a análise de documentos, identificados com 'ADD' + numero do requisito, e com a seguinte legenda de categoria:

RF: Requisitos Funcionais - Descrevem o comportamento ou a funcionalidade que o software deve ter para atender às necessidades do usuário.

RNF: Requisitos Não-Funcionais - Descrevem os atributos que o software deve ter, como desempenho, segurança e usabilidade, mas não descrevem o comportamento do software em si.

RI: Requisitos de Interface - Descrevem as características da interface do usuário, como layout, navegação e personalização.

RPR: Requisitos de Produto - Descrevem as características do produto, como compatibilidade, desempenho e custo.

RR: Riscos - São os riscos associados ao desenvolvimento e uso do software.

RT: Testes e Validações - Descrevem as atividades necessárias para testar e validar o software antes de sua implantação.

| Número do Requisito | Categoria              | Descrição                                                   |
|---------------------|------------------------|-------------------------------------------------------------|
| ADD1                | RF                     | Baixar o aplicativo em sistemas Android (versão 5 ou superior) e iOS.           |
| ADD2                | RF                     | Permitir cadastro no Portal de Serviços, exigindo um endereço de e-mail válido.   |
| ADD3                | RF                     | Oferecer opção de alteração de senha no aplicativo.       |
| ADD4                | RF                     | Disponibilizar variedade de serviços relacionados à CNH e veículos.               |
| ADD5                | RNF                    | Garantir compatibilidade com Android 5 ou superior.        |
| ADD6                | RNF                    | Assegurar compatibilidade com iOS.                          |
| ADD7                | RI                     | Projetar interface fácil de usar para cadastro no Portal de Serviços.             |
| ADD8                | RI                     | Criar interface para alteração de senha de forma intuitiva e segura.              |
| ADD9                | RI                     | Apresentar opções de serviço de forma clara e acessível aos usuários.            |
| ADD10               | RPR                    | Garantir desempenho aceitável em dispositivos Android e iOS.                        |
| ADD11               | RR                     | Risco associado à segurança da alteração de senha e envio de e-mails.             |
| ADD12               | RT                     | Realizar testes para validação de funcionalidades do aplicativo.                  |

| Versão | Data       | Autor             | Alterações                                          | Revisor        |
| ------ | ---------- | ----------------- | --------------------------------------------------- | -------------- |
| 1.0    | 03/10/2023 | João Pedro Anacleto | Criação do documento                |  |