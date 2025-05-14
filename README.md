
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

## 🧾 Requisitos Funcionais

| Identificador | Descrição | Dependência |
|---------------|-----------|-------------|
| RF01 | Cadastro de Empresa - O sistema deve permitir o cadastro de empresas, exigindo nome da empresa, CNPJ, e-mail, telefone, endereço e senha de acesso. ||
| RF02 | Cadastro de Facção - O sistema deve permitir o cadastro de facções, exigindo nome da facção, nome do responsável, CNPJ, e-mail, telefone, endereço, tipo de serviço oferecido e senha de acesso. ||
| RF03 | Cadastro de Faccionista - O sistema deve permitir o cadastro de faccionistas, exigindo nome completo, e-mail, telefone, endereço, principal serviço oferecido e senha de acesso. Com a opção de escolha entre se vincular a uma facção ou atuar de forma autônoma. ||
| RF04 | Cadastro de Serviços - O sistema deve permitir o cadastro de serviços, exigindo tipo de serviço, descrição e prazo para conclusão. ||
| RF05 | Solicitação de Serviço - O sistema deve permitir que uma empresa envie uma solicitação de serviço para uma facção, especificando o tipo de serviço, a descrição, o prazo desejado e os detalhes da demanda. A facção deve poder aceitar ou recusar a solicitação. ||
| RF06 | Visualização de Facções – O sistema deve permitir a visualização das facções cadastradas, exibindo as informações fornecidas no momento do cadastro, com exceção do CNPJ. Além disso, devem ser apresentadas a quantidade de serviços realizados, a nota média de avaliação, o tempo de permanência na plataforma, o último acesso registrado, a região de atendimento e a disponibilidade atual para novos trabalhos. ||
| RF07 | Histórico de Serviços - O sistema deve manter um histórico de todos os serviços realizados, acessível para a facção, faccionista e empresa. Esse histórico deve incluir o nome do serviço, as datas de início e conclusão, e as avaliações recebidas por cada serviço. O histórico deve estar disponível a qualquer momento para consulta. ||
| RF08 | Chat entre Empresa e Facção - O sistema deve permitir que a empresa e a facção se comuniquem diretamente por meio de um chat integrado, facilitando a troca de informações e negociação de serviços. A comunicação deve ser restrita apenas a esses dois perfis, sem possibilidade de interação direta entre a empresa e faccionista. ||
| RF09 | Chat entre Facção e Faccionista - O sistema deve permitir que a facção e o faccionista se comuniquem diretamente por meio de um chat integrado, permitindo a troca de informações sobre serviços e demandas. ||
| RF10 | Avaliação e Feedback - O sistema deve solicitar que, ao final de um serviço, o usuário avalie a outra parte envolvida com base em critérios específicos. A avaliação deve incluir uma nota geral, em uma escala de 1 a 5, considerando qualidade, cumprimento de prazos, comunicação e grau de confiabilidade. ||
| RF11 | Notificar Empresas - O sistema deve notificar a empresa sempre que uma facção responder a uma proposta ou houver alterações no status de um pedido. Também deve receber notificações sobre avaliações de serviços finalizados e, quando aplicável, recomendações personalizadas de facções com base no histórico de uso da plataforma. ||
| RF12 | Notificar Facções/Faccionistas – O sistema deve notificar uma facção e faccionista sempre que houver novas solicitações de serviço, mensagens recebidas ou avaliações feitas. Além disso, deve alertar sobre a proximidade de prazos e enviar notificações sempre que houver feedbacks sobre o serviço prestado. ||
| RF13 | Prazos e Entregas – O sistema deve permitir o registro das datas de entrega e a atualização do status do serviço sempre que a facção declarar a entrega parcial ou total. ||


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
