# AtendimentoConsultorio

Esse projeto consiste em um sistema de atendimento ao cliente para consultórios médicos.

A parte do Back-End engloba uma API em C# do zero utilizando o padrão DDD (Domain Driven Design), fazendo um CRUD das entidades. Foi utilizado o SQL Server como banco de dados.

Segue abaixo o repositório do Back-End:
https://github.com/Diego-S-G/AtendimentoConsultorio-backend

A parte do Front-End foi feita em Angular, conectando-se a API e utilizando seus EndPoints para manipular os dados.

Segue abaixo o repositório do Front-End:
https://github.com/Diego-S-G/AtendimentoConsultorio_front



Abaixo está o funcionamento do sistema:


Exemplo de CRUD com Médicos - 
https://github.com/Diego-S-G/AtendimentoConsultorio/assets/140908243/3a1d4f6a-fcb1-4b2b-b667-db777561e2bd


Exemplo de CRUD com Pacientes - 
https://github.com/Diego-S-G/AtendimentoConsultorio/assets/140908243/b4cf7eac-c55b-449d-9266-f4c42d806662


Exemplo de CRUD com Salas - 
https://github.com/Diego-S-G/AtendimentoConsultorio/assets/140908243/a2fbb141-d964-4613-beff-5178be9a7400


Exemplo de CRUD com Atendimentos-
https://github.com/Diego-S-G/AtendimentoConsultorio/assets/140908243/30d54f7f-5431-4ae7-9782-467b0a899605



Exemplo de funcionamento do sistema com a tela de apresentação de atendimentos, que é a parte exposta ao cliente - 
https://github.com/Diego-S-G/AtendimentoConsultorio/assets/140908243/d72da374-f5c5-4ea9-b5e1-bde21d0c0445


https://github.com/Diego-S-G/AtendimentoConsultorio/assets/140908243/4664bc1a-a667-4aa9-9d67-4a4f0e4ab217


https://github.com/Diego-S-G/AtendimentoConsultorio/assets/140908243/99f79ac0-f841-4c1d-b04b-9a83eba26325


Ao iniciar um atendimento, ele cai na página de apresentação. Caso seja cancelado ou finalizado, cai na tabela com os últimos três atendimentos que foram finalizados ou cancelados. Ao iniciar outros atendimentos, o mais recente fica em destaque enquanto os outros ficam em uma tabela ao lado com os atendimentos em andamento.
