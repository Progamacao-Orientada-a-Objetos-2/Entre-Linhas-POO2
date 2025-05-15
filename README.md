
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
| RF05 | Busca de Facções – O sistema deve permitir que qualquer usuário da plataforma realize buscas por facções cadastradas, utilizando filtros como região, tipo de serviço, histórico de avaliações e disponibilidade. ||
| RF06 | Busca de Faccionistas e Empresas (restrita à Facção) – O sistema deve permitir que apenas facções realizem buscas por faccionistas e empresas cadastradas, utilizando filtros como região, tipo de serviço, histórico de avaliações e disponibilidade. ||
| RF07 | Solicitação de Serviço - O sistema deve permitir que uma empresa envie uma solicitação de serviço para uma facção, especificando o tipo de serviço, a descrição, o prazo desejado e os detalhes da demanda. A facção deve poder aceitar ou recusar a solicitação. ||
| RF08 | Visualização de Facções – O sistema deve permitir a visualização das facções cadastradas, exibindo informações como a quantidade de serviços realizados, a nota média de avaliação, a data do último acesso, a região de atendimento e a disponibilidade atual para novos trabalhos. ||
| RF09 | Histórico de Serviços – O sistema deve manter um registro completo de todos os serviços realizados, acessível a qualquer momento por facções, faccionistas e empresas. Esse histórico deve incluir o nome do serviço, as datas de início e conclusão, além das avaliações recebidas. ||
| RF10 | Chat entre Empresa e Facção - O sistema deve permitir que a empresa e a facção se comuniquem diretamente por meio de um chat integrado, facilitando a troca de informações e negociação de serviços. A comunicação deve ser restrita apenas a esses dois perfis, sem possibilidade de interação direta entre a empresa e faccionista. ||
| RF11 | Chat entre Facção e Faccionista - O sistema deve permitir que a facção e o faccionista se comuniquem diretamente por meio de um chat integrado, permitindo a troca de informações sobre serviços e demandas. ||
| RF12 | Avaliação e Feedback - O sistema deve solicitar que, ao final de um serviço, o usuário avalie a outra parte envolvida. A avaliação deve incluir uma nota geral, de 1 a 5, levando em conta a qualidade do serviço, o cumprimento de prazos, comunicação e grau de confiabilidade. ||
| RF13 | Notificar Empresas – O sistema deve enviar notificações para a empresa sempre que uma facção responder a uma proposta, houver alterações no status de um pedido ou forem registradas novas avaliações. Quando aplicável, também devem ser enviadas recomendações personalizadas de facções com base no histórico de uso da plataforma. ||
| RF14 | Notificar Facções/Faccionistas – O sistema deve notificar uma facção e faccionista sempre que houver novas solicitações de serviço, mensagens recebidas ou avaliações feitas. Além disso, deve alertar sobre a proximidade de prazos e enviar notificações sempre que houver feedbacks sobre o serviço prestado. ||
| RF15 | Prazos e Entregas – O sistema deve permitir o registro das datas de entrega e a atualização do status do serviço sempre que a facção declarar a entrega parcial ou total. ||

***2.2. Requisitos Não Funcionais***

## ⚙️ Requisitos Não Funcionais

| Identificador | Descrição | Dependência |
|---------------|-----------|-------------|
| RNF01 | O sistema deve suportar até 2.000 usuários simultâneos, com tempo de resposta de até 3 segundos por ação, mesmo em pico de uso. ||
| RNF02 | O sistema deve ser escalável, suportando crescimento de usuários e dados sem comprometer o desempenho. ||
| RNF03 | O sistema deve permitir o preenchimento por comandos de voz em dispositivos móveis compatíveis, especialmente em campos de cadastro e formulários básicos. ||
| RNF04 | A interface deve ser intuitiva, com design responsivo e usabilidade voltada a usuários com pouca familiaridade com tecnologia. ||
| RNF05 | O sistema deve garantir acessibilidade total, permitindo navegação completa via teclado, compatibilidade com leitores de tela e uso de marcação semântica adequada. ||
| RNF06 | As notificações devem ser entregues ao usuário em até 5 segundos após a ocorrência do evento. ||
| RNF07 | O sistema deve cumprir todas as leis de proteção de dados, como a LGPD, garantindo a privacidade e segurança das informações dos usuários. ||
| RNF08 | Os dados dos usuários devem ser protegidos por criptografia, com autenticação em dois fatores, controle de acesso restrito e mascaramento de informações sensíveis na interface. ||
| RNF09 | O sistema deve registrar logs de acesso e ações para garantir auditoria e segurança. ||
| RNF10 | O sistema deve garantir segurança na autenticação, bloqueando o acesso temporariamente após 5 tentativas falhas consecutivas e expirando a sessão após 30 minutos de inatividade. ||
| RNF11 | O sistema deve permitir o uso offline para consulta das informações básicas já carregadas. ||
| RNF12 | O sistema deve realizar backups automáticos diários, com possibilidade de restaurar dados excluídos em até 7 dias. ||
| RNF13 | O sistema deve manter disponibilidade mínima de 99,5%, exceto durante manutenções programadas. ||
| RNF14 | O sistema deve ser totalmente restaurado e funcional em até 4 horas após qualquer falha, minimizando o impacto para os usuários e garantindo continuidade dos serviços. ||
| RNF15 | O sistema deve monitorar continuamente sua performance e segurança, enviando alertas automáticos à equipe técnica em caso de anomalias, falhas ou tentativas suspeitas de acesso. ||


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
