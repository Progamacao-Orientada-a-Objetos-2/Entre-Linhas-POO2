
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

***1.3. Descrição dos Usuários***

O sistema **Entre Linhas** é utilizado por três perfis principais de usuários finais: **faccionistas**, **facções** e **empresas**. Cada um desempenha um papel específico dentro da plataforma e possui necessidades distintas, que foram consideradas na definição dos requisitos e funcionalidades.

---

#### 1. Faccionistas

**Perfil:**  
Costureiras autônomas, geralmente com experiência prática, mas com pouca familiaridade com ferramentas digitais complexas. Em sua maioria, utilizam o celular como principal meio de comunicação e trabalho.

**Persona:**  
*Maria*, 42 anos, costureira há mais de 15 anos, participa de pequenos grupos informais, mas quer ter mais estabilidade e facilidade para encontrar serviços. Usa o WhatsApp com frequência e tem dificuldade para organizar suas oportunidades de trabalho.

**Análise de tarefas:**  
A faccionista busca facções ativas para se integrar e receber demandas. Ela precisa visualizar oportunidades de forma clara, saber os detalhes do serviço (tipo de peça, prazo, valor) e se candidatar com facilidade. Além disso, espera acompanhar o andamento do trabalho e se comunicar com sua facção dentro do próprio app.

---

#### 2. Facção

**Perfil:**  
Grupos liderados por uma ou mais pessoas que organizam equipes de faccionistas para atender demandas de empresas. Geralmente são experientes na produção em escala, mas enfrentam dificuldades para recrutar novas costureiras e negociar com empresas.

**Persona:**  
*Joana*, 38 anos, lidera uma facção há 5 anos. Já trabalhou com diversas empresas, mas sente dificuldade em reunir costureiras rapidamente quando surge uma nova demanda. Perde tempo buscando contatos e organizando o trabalho manualmente.

**Análise de tarefas:**  
A facção precisa recrutar faccionistas para sua equipe, responder a propostas de empresas, negociar condições e gerenciar os serviços em andamento. Espera encontrar ferramentas para facilitar o controle da produção e a comunicação com todos os envolvidos.

---

#### 3. Empresa

**Perfil:**  
Confecções e negócios do setor de moda que terceirizam serviços de costura por meio de facções. Buscam agilidade, qualidade e confiança nas entregas. Preferem soluções centralizadas que reduzam a dependência de contatos informais.

**Persona:**  
*Fernanda*, 34 anos, gerente de produção em uma marca de roupas femininas. Já perdeu prazos por não conseguir fechar com facções a tempo. Quer um sistema confiável para encontrar parceiros rapidamente e acompanhar os pedidos de forma transparente.

**Análise de tarefas:**  
A empresa deseja buscar e selecionar facções com base em critérios como tipo de serviço, localização e avaliações. Também precisa negociar pedidos, acompanhar o progresso da produção e manter um histórico de serviços prestados.

***Personas:***

[Personas.zip](https://github.com/user-attachments/files/20257902/Personas.zip)


***Análise da situação atual: antes da introdução de sua solução***

As pessoas normalmente trabalham via WhatsApp, sem a praticidade e facilidade de encontrar os serviços, dependendo de quem elas conhecem e vice-versa. Os artefatos em específico não teria algum, seria basicamente o WhatsApp. E o que elas precisam saber é onde achar as respectivas faccionistas, facções, clientes e, o seu tipo de serviço.

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

Buscam com simplicidade a sua especificação de serviço ou mesmo alguém para prestar esse serviço. Os artefatos envolvidos é: o app por si só e todas suas funcionalidades. Para o uso do mesmo é necessário somente de um básico conhecimento no uso do telefone celular

***Cenário: Antes***

#### Faccionista  
Maria começa o dia cedo, como sempre. Liga a máquina, ajeita os tecidos, mas sente um peso no peito: mais um dia sem saber se vai ter serviço. Ela abre os grupos de WhatsApp, procura por alguma facção que precise de mais uma costureira, mas tudo é confuso e incerto. Às vezes até vê uma oportunidade, mas não tem como saber se ainda está disponível, nem quem está organizando. O sentimento é de invisibilidade — ela quer trabalhar, mas ninguém parece enxergar isso.

#### Facção  
Do outro lado da cidade, Joana lidera uma pequena facção. Ela tenta fechar um serviço com uma empresa conhecida, mas esbarra em um problema constante: não consegue encontrar costureiras disponíveis com rapidez. Vai atrás de contatos antigos, manda mensagens em grupos diferentes, espera respostas que às vezes nem chegam. Ela sabe que a demanda existe, mas montar a equipe a tempo vira uma corrida contra o relógio, cheia de incertezas.

#### Empresa  
Fernanda, responsável por uma confecção, acorda já preocupada. Precisa de uma nova facção para produzir a próxima coleção, mas não sabe por onde começar. Volta aos grupos de WhatsApp, revira contatos salvos e tenta lembrar o nome daquela facção que fez um bom trabalho meses atrás. Mas nada é prático. Tudo depende de indicações, mensagens demoradas e tentativas frustradas. Ela sente que perde tempo demais tentando encontrar alguém confiável.

---

***Cenário: Depois***

#### Faccionista  
Maria acorda com o celular vibrando: uma nova facção está recrutando costureiras para um projeto que começa ainda essa semana. Ela abre o app *Entre Linhas*, vê os detalhes, gosta do que lê e envia sua solicitação com um clique. Pouco tempo depois, é aceita. A líder da facção envia uma mensagem direta pelo app e explica como será a divisão das peças. Maria sente um alívio gostoso — agora ela não precisa correr atrás de trabalho, o trabalho encontra ela.

#### Facção  
Joana abre o *Entre Linhas* com o café ainda na mão. Uma empresa acaba de publicar um novo pedido de produção, e ela vê que o perfil da sua facção se encaixa perfeitamente. Responde de forma rápida, envia seu portfólio e recebe retorno da empresa em minutos. Em seguida, acessa a aba de faccionistas e recruta três novas costureiras para completar a equipe. Em poucas horas, tudo está organizado. Ela sente que, finalmente, tem controle do processo.

#### Empresa  
Fernanda acessa o app logo cedo e digita o que precisa: uma facção com experiência em moda feminina, entrega rápida e boa avaliação. Em segundos, aparecem várias opções. Ela escolhe uma, conversa diretamente com a responsável e fecha o serviço. Tudo documentado, com prazos e valores definidos desde o início. Pela primeira vez, sente que o processo foi leve — sem perda de tempo, sem improvisos, só parceria e profissionalismo.

## 2. Documentos gerais no repositório

***2.1. ⚙️ Requisitos Funcionais***

| Identificador | Descrição | Dependência | Prioridade |
|---------------|-----------|-------------|------------|
| **RF01** | **Cadastro de Empresa** – O sistema deve permitir o cadastro de empresas, exigindo os seguintes dados obrigatórios: nome da empresa, CNPJ válido (com verificação de formato e duplicidade), e-mail válido (com validação de formato), número de telefone no padrão nacional, endereço completo e senha de acesso com no mínimo 8 caracteres. | – | M |
| **RF02** | **Cadastro de Facção** – O sistema deve permitir o cadastro de facções, exigindo nome da facção, nome do responsável, CNPJ, e-mail, telefone, endereço, tipo de serviço oferecido e senha de acesso. | – | M |
| **RF03** | **Cadastro de Faccionista** – O sistema deve permitir o cadastro de faccionistas, exigindo nome completo, e-mail, telefone, endereço, principal serviço oferecido e senha de acesso. Com a opção de escolha entre se vincular a uma facção ou atuar de forma autônoma. | RF02 | M |
| **RF04** | **Cadastro de Serviços** – O sistema deve permitir que empresas cadastrem serviços, exigindo tipo de serviço, descrição e prazo para conclusão. | RF01 | M |
| **RF05** | **Busca de Facções** – O sistema deve permitir que qualquer usuário da plataforma realize buscas por facções cadastradas, utilizando filtros como região, tipo de serviço, histórico de avaliações e disponibilidade. | RF02 | S |
| **RF06** | **Busca de Faccionistas e Empresas (restrita à Facção)** – O sistema deve permitir que apenas facções realizem buscas por faccionistas e empresas cadastradas, utilizando filtros como região, tipo de serviço, histórico de avaliações e disponibilidade. | RF01, RF03 | S |
| **RF07** | **Solicitação de Serviço** – O sistema deve permitir que uma empresa envie uma solicitação de serviço para uma facção, especificando o tipo de serviço, a descrição, o prazo desejado e os detalhes da demanda. A facção deve poder aceitar ou recusar a solicitação. | RF01, RF02, RF04 | M |
| **RF08** | **Visualização de Perfil** – O sistema deve permitir que qualquer usuário logado na plataforma visualize os perfis cadastrados. As informações exibidas devem incluir: quantidade de serviços realizados, nota média de avaliação, data do último acesso, região de atendimento e disponibilidade atual para novos trabalhos. A visualização está restrita a usuários autenticados. | RF01–RF04, RF12 | S |
| **RF09** | **Histórico de Serviços** – O sistema deve manter um registro completo de todos os serviços realizados. Esse histórico deve ser acessível, a qualquer momento, por qualquer usuário, contendo apenas os serviços dos quais participaram diretamente. Cada registro deve incluir o nome do serviço, as datas de início e conclusão, além das avaliações recebidas. | RF01, RF02, RF04, RF07, RF12, RF15 | M |
| **RF10** | **Chat entre Empresa e Facção** – O sistema deve permitir que a empresa e a facção se comuniquem diretamente por meio de um chat integrado, facilitando a troca de informações e negociação de serviços. A comunicação deve ser restrita apenas a esses dois perfis, sem possibilidade de interação direta entre a empresa e faccionista. | RF01, RF02 | S |
| **RF11** | **Chat entre Facção e Faccionista** – O sistema deve permitir que a facção e o faccionista se comuniquem diretamente por meio de um chat integrado, permitindo a troca de informações sobre serviços e demandas. | RF02, RF03 | S |
| **RF12** | **Avaliação e Feedback** – O sistema deve solicitar obrigatoriamente que, ao final de cada serviço concluído, o usuário avalie a outra parte envolvida. A avaliação deve incluir uma nota geral, de 1 a 5, considerando a qualidade do serviço, comunicação e grau de confiabilidade. A avaliação será um requisito para finalizar a transação. | RF01, RF02, RF04, RF07, RF09 | M |
| **RF13** | **Notificar Empresas** – O sistema deve enviar notificações para a empresa sempre que uma facção responder a uma proposta, houver alterações no status de um pedido ou forem registradas novas avaliações. Quando aplicável, também devem ser enviadas recomendações personalizadas de facções com base no histórico de uso da plataforma. | RF01, RF02, RF04, RF07, RF09, RF10, RF12 | C |
| **RF14** | **Notificar Facções/Faccionistas** – O sistema deve notificar uma facção e faccionista sempre que houver novas solicitações de serviço, mensagens recebidas ou avaliações feitas. Além disso, deve alertar sobre a proximidade de prazos e enviar notificações sempre que houver feedbacks sobre o serviço prestado. | RF02–RF04, RF07, RF10–RF12 | C |
| **RF15** | **Prazos e Entregas** – O sistema deve permitir o registro das datas de entrega e a atualização do status do serviço sempre que a facção declarar a entrega parcial ou total. | RF02, RF04, RF07 | M |

---

***2.2. 🧾 Requisitos Não Funcionais***

| Identificador | Descrição | Dependência | Prioridade |
|---------------|-----------|-------------|------------|
| **RNF01** | O sistema deve suportar até 2.000 usuários simultâneos, com tempo de resposta de até 3 segundos por ação, mesmo em pico de uso. | RNF02, RNF13, RNF15 | M |
| **RNF02** | O sistema deve ser escalável, suportando crescimento de usuários e dados sem comprometer o desempenho. | RNF13, RNF14 | M |
| **RNF03** | O sistema deve permitir o preenchimento por comandos de voz em dispositivos móveis compatíveis, especialmente em campos de cadastro e formulários básicos. | RF01–RF04 | C |
| **RNF04** | A interface deve ser intuitiva, com design responsivo e usabilidade voltada a usuários com pouca familiaridade com tecnologia. | RF01–RF12 | M |
| **RNF05** | O sistema deve garantir acessibilidade, permitindo navegação completa via teclado, compatibilidade com leitores de tela e uso de marcação semântica adequada. | RF01–RF15 | S |
| **RNF06** | As notificações devem ser entregues ao usuário em até 5 segundos após a ocorrência do evento. | RF13, RF14 | S |
| **RNF07** | O sistema deve cumprir todas as leis de proteção de dados, como a LGPD, garantindo a privacidade e segurança das informações dos usuários. | RF01–RF03 | M |
| **RNF08** | Os dados dos usuários devem ser protegidos por criptografia, com autenticação em dois fatores, controle de acesso restrito e mascaramento de informações sensíveis na interface. | RF01–RF03, RF10, RF11 | M |
| **RNF09** | O sistema deve registrar logs de acesso e ações para garantir auditoria e segurança. | RF07, RF13 | S |
| **RNF10** | O sistema deve garantir segurança na autenticação, bloqueando o acesso temporariamente após 5 tentativas falhas consecutivas e expirando a sessão após 30 minutos de inatividade. | RF01–RF03 | M |
| **RNF11** | O sistema deve permitir o uso offline para consulta das informações básicas já carregadas. | RF08, RF09 | C |
| **RNF12** | O sistema deve realizar backups automáticos diários, com possibilidade de restaurar dados excluídos em até 7 dias. | RF09 | S |
| **RNF13** | O sistema deve manter disponibilidade mínima de 99,5%, exceto durante manutenções programadas. | RNF01, RNF02, RNF14, RNF15 | M |
| **RNF14** | O sistema deve ser totalmente restaurado e funcional em até 4 horas após qualquer falha, minimizando o impacto para os usuários e garantindo continuidade dos serviços. | RNF12, RNF13 | S |
| **RNF15** | O sistema deve monitorar continuamente sua performance e segurança, enviando alertas automáticos à equipe técnica em caso de anomalias, falhas ou tentativas suspeitas de acesso. | RNF01, RNF02, RNF13 | S |



***2.3. Perguntas***

***Perguntas:*** [Perguntas.pdf](https://github.com/user-attachments/files/20257828/Perguntas.pdf)

***2.4. Entrevista***

***Entrevista transcrita:*** [TranscricaoEntrevista.pdf](https://github.com/user-attachments/files/20446707/TranscricaoEntrevista.pdf)


***Entrevista vídeo:*** [Vídeo](https://drive.google.com/file/d/1tO4Hgw7EJtW-JnMKMMNHgONT8ySa3wVI/view?usp=drive_link)

***2.5. Histórias do Usuário***

***Histórias do Usuário:*** [Historias_de_Usuario.pdf](https://github.com/user-attachments/files/20767059/Historias_de_Usuario.pdf)

***2.6. Diagramas de Caso de Uso e Especificações***

***Diagramas de Casos de Uso:*** [Caso de Uso - Entre Linhas.pdf](https://github.com/user-attachments/files/20730097/Caso.de.Uso.-.Entre.Linhas.pdf)

***Descrição dos Diagramas de Casos de Uso:*** [Descrição Caso de Uso - Entre Linhas.pdf](https://github.com/user-attachments/files/20730106/Descricao.Caso.de.Uso.-.Entre.Linhas.pdf)


***2.7. Diagramas de Atividades***

***Diagramas de Atividades:*** [Diagrama_de_Atividade](https://github.com/user-attachments/assets/28ccf25b-0865-45e8-814b-b0475db1bfaa)

***2.9. Protótipos***

***Protótipo:*** [Prototipo.pdf](https://github.com/user-attachments/files/20767284/Prototipo.pdf)
