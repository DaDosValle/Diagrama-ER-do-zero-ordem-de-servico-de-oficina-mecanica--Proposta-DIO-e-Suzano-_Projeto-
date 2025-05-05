Projeto proposto pelo bootcamp Analise de Dados Suzano via DIO

Diagrama Entidade Relacionamento conceitual para o contexto de oficina

Este projeto faz parte do meu aprendizado do bootcamp Suzano em parceria com DIO. Ele simula a modelagem (ER) de um sistema completo de banco de dados para sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.
Projeto foi idealizado do zero seguindo os requisitos apresentados no curso.

Objetivo
Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida.
Narrativa:
•	Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
•	Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
•	Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
•	A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
•	O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
•	A mesma equipe avalia e executa os serviços
•	Os mecânicos possuem código, nome, endereço e especialidade
•	Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.



Ferramentas/tecnologias utilizadas:
- MySQL Workbench
- Notação DER (Diagrama Entidade-Relacionamento)

Criado por mim: Fernando M. do Valle (https://github.com/DaDosValle)
