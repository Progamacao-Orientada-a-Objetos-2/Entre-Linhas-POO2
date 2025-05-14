
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

***Link ->*** [Padlet](https://padlet.com/joaoabreu19/projeto-requisitos-24nxemxvq4j1auom)

## 1. Introdução

NOME                                |Github
------------------------------------|----------------------------------------
João Lucas Silva de Souza           | [JoaoLucas-Silva](https://github.com/JoaoLucas-Silva)
João Vitor Oliveira Abreu           | [jvoabreu](https://github.com/jvoabreu)
José Wynder Alves Hernandes         | [JoseWynder](https://github.com/JoseWynder)
Jean Alves Rocha                    | [JeanAlvesR](https://github.com/JeanAlvesR)
Luan Henrique de Almeida dos Santos | [luanalmeida7](https://github.com/luanalmeida7)
----------------------------------------------------------------------------



***1.2.  Nome do Sistema***

#### $Entre Linhas$

***1.3.  Propósito do Sistema***

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela *`Entre Linhas`*, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema `Entre Linhas` é ajudar costureiras que trabalham na modalidade de facção, facilitando o contato entre quem obtém uma facção, entre as faccionistas, e a empresa que busca por esse serviço de costura. O sistema tem como característica principal a simplicidade e facilidade para quem o necessita, esse é o principal diferencial.

***1.2.  Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes, costureiras de qualquer faixa etária e, qualquer tipo de serviço (que envolva a costura).

***1.3. Descrição dos usuários***

*<Descrever quais os usuários finais do sistema (quem vai utilizar o sistema). Neste espaço vocês vão traçar um perfil de usuário, bem como as personas e análide de tarefas>*

***Personas:***

*<Imagem, arquivo (PDF), link com as Personas.>*

***Análise da situação atual: antes da introdução de sua solução***

As pessoas normalmente trabalham via WhatsApp, sem a praticidade e facilidade de encontrar os serviços, dependendo de quem elas conhecem e vice-versa. Os artefatos em específico não teria algum, seria basicamente o WhatsApp. E o que elas precisam saber é onde achar as respectivas faccionistas, facções, clientes e, o seu tipo de serviço.

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

Buscam com simplicidade a sua especificação de serviço ou mesmo alguém para prestar esse serviço. Os artefatos envolvidos é: o app por si só e todas suas funcionalidades. Para o uso do mesmo é necessário somente de um básico conhecimento no uso do telefone celular

***Cenário: Antes***

*<Preencher com o cenário idealizado antes da aplicação do seu sistema.>*

***Cenário: Depois***

*<Preencher com o cenário idealizado depois da aplicação do seu sistema.>*

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

## 🧾 Requisitos Funcionais e Prioridades

| Código | Requisito | Prioridade |
|--------|-----------|------------|
| RF01 | Cadastro de Empresa/Cliente - O sistema deve permitir o cadastro de empresas, exigindo nome da empresa, CNPJ, e-mail, telefone e endereço. | 🔴 **Alta** |
| RF02 | Cadastro de Facção - O sistema deve permitir o cadastro de facções, exigindo CNPJ, nome do responsável, endereço e cidade, com a possibilidade de atualizações futuras. | 🔴 **Alta** |
| RF03 | Cadastro de Faccionista - O sistema deve permitir o cadastro de faccionistas, com a informação sobre a existência de uma facção vinculada ou atuação de forma autônoma. | 🔴 **Alta** |
| RF04 | Cadastro de Serviços - O sistema deve permitir o cadastro de serviços, exigindo tipo de serviço, descrição e prazo para conclusão. | 🔴 **Alta** |
| RF05 | Visualização de Facções - O sistema deve permitir a visualização das facções cadastradas, exibindo o tipo de serviço, a quantidade de serviços realizados, a nota média e a quantidade de avaliações recebidas. | 🟡 **Média** |
| RF06 | Avaliação e Feedback - O sistema deve permitir que o cliente avalie o serviço após a entrega, considerando qualidade, cumprimento de prazo e atendimento, utilizando uma escala de 1 a 5. | 🟡 **Média** |
| RF07 | Notificações e Alertas - O sistema deve enviar notificações para facções sempre que atenderem aos requisitos de um serviço, e para faccionistas autônomos sempre que uma facção precisar de seus serviços. | 🟢 **Baixa** |
| RF08 | Chat para Contrato de Serviços - O sistema deve disponibilizar um chat para comunicação entre empresa e facção após a aceitação da solicitação, exibido na área de serviços da empresa. | 🟡 **Média** |
| RF09 | Prazos e Entregas - O sistema deve permitir o registro das datas de entrega e atualizar o status do serviço conforme a facção declarar entrega parcial ou total, notificando a empresa quando o serviço for concluído. | 🔴 **Alta** |
| RF10 | Histórico de Serviços - O sistema deve manter um histórico dos serviços realizados por cada usuário, acessível pelas empresas, facções e faccionistas em suas respectivas áreas logadas, contendo tipo de serviço, data de entrega, nome da outra parte envolvida e avaliação. | 🟡 **Média** |


***2.2. Requisitos Não Funcionais***

## ⚙️ Requisitos Não Funcionais e Prioridades

| Código | Requisito | Prioridade |
|--------|-----------|------------|
| RNF01 | Desempenho - O sistema deve ser capaz de suportar até 2.000 usuários simultâneos sem perda de desempenho, com ações que não demorem mais que 3 segundos. | 🔴 **Alta** |
| RNF02 | Usabilidade - A interface do sistema deve ser simples e fácil de usar, mesmo para usuários com pouco conhecimento em tecnologia, e o sistema deve ser otimizado para smartphones e tablets. | 🔴 **Alta** |
| RNF03 | Segurança - Os dados dos usuários devem ser protegidos por criptografia, e a autenticação deve exigir senhas fortes, com a opção de autenticação em duas etapas. | 🔴 **Alta** |
| RNF04 | Backup e Recuperação - O sistema deve realizar backups automáticos diariamente e permitir a recuperação de dados excluídos acidentalmente até 7 dias após a exclusão. | 🟡 **Média** |
| RNF05 | Disponibilidade - O sistema deve estar disponível constantemente, exceto durante manutenções programadas, e funcionar de forma eficaz em áreas com conexões de internet lentas. | 🔴 **Alta** |
| RNF06 | Compatibilidade - O sistema deve ser compatível com os navegadores mais populares e com dispositivos Android e iOS, proporcionando uma boa experiência de usuário. | 🟡 **Média** |
| RNF07 | Localização e Idioma - O sistema deve estar disponível em português e permitir a adição de outros idiomas, caso necessário. A data e hora devem ser exibidas de acordo com a localidade do usuário. | 🟢 **Baixa** |
| RNF08 | Manutenção e Suporte - O sistema deve ser de fácil manutenção e atualização, e deve fornecer suporte técnico com resposta garantida em até 24 horas. | 🟡 **Média** |
| RNF09 | Conformidade - O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD) e ser acessível a pessoas com deficiência. | 🔴 **Alta** |
| RNF10 | Atualizações - O sistema deve permitir atualizações contínuas sem interrupções, garantindo que melhorias sejam feitas sem afetar a experiência do usuário. | 🟡 **Média** |


***2.3. Perguntas***

*<Arquivo com as perguntas realizadas na entrevista .>*

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***

*<Imagem, arquivo (PDF), link com as Histórias de Usuário.>*

***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

***2.9. Protótipos***

*<Imagem, arquivo (PDF), link com Protótipo.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
