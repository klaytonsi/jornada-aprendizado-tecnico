SQL Playground — FreeAcademy

🇧🇷 Português

O que estudei

Nesta etapa, conheci o SQL Playground utilizado para praticar consultas SQL de forma interativa.

Aprendi a identificar as principais partes do ambiente:

- Schema Panel: mostra as tabelas disponíveis e suas colunas.
- Editor: local onde escrevo as consultas SQL.
- Results: exibe o resultado da consulta executada.

Também conheci a tabela "users", utilizada nos primeiros exercícios:

Coluna| Descrição
"id"| Identificador único do usuário
"name"| Nome completo
"email"| E-mail
"age"| Idade
"city"| Cidade
"created_at"| Data de criação da conta

Consultas praticadas

Consulta de todas as colunas e registros:

SELECT * FROM users;

Seleção de colunas específicas:

SELECT name, email
FROM users;

Filtragem de usuários por cidade:

SELECT *
FROM users
WHERE city = 'New York';

Contagem de registros:

SELECT COUNT(*)
FROM users;

O que aprendi

Nesta prática, comecei a entender a estrutura básica de uma consulta SQL:

- "SELECT" define os dados que quero consultar.
- "FROM" indica a tabela utilizada.
- "WHERE" permite filtrar registros.
- "COUNT(*)" permite contar registros.

Também pratiquei a execução das consultas diretamente no SQL Playground.

Observações

Aprendi que palavras-chave SQL podem ser escritas em maiúsculas ou minúsculas, mas o uso de maiúsculas para comandos SQL é uma convenção comum e facilita a leitura das consultas.

Próximo passo

Continuar praticando consultas com "SELECT" antes de avançar para outros conceitos de SQL.

---

🇺🇸 English

What I studied

In this stage, I learned about the SQL Playground used to practice SQL queries interactively.

I learned to identify the main parts of the environment:

- Schema Panel: shows the available tables and their columns.
- Editor: where SQL queries are written.
- Results: displays the result of the executed query.

I also explored the "users" table used in the first exercises:

Column| Description
"id"| Unique user identifier
"name"| Full name
"email"| Email address
"age"| Age
"city"| City
"created_at"| Account creation date

Queries practiced

Selecting all columns and records:

SELECT * FROM users;

Selecting specific columns:

SELECT name, email
FROM users;

Filtering users by city:

SELECT *
FROM users
WHERE city = 'New York';

Counting records:

SELECT COUNT(*)
FROM users;

What I learned

In this practice, I started understanding the basic structure of a SQL query:

- "SELECT" defines the data I want to retrieve.
- "FROM" indicates the table being queried.
- "WHERE" allows records to be filtered.
- "COUNT(*)" allows records to be counted.

I also practiced executing queries directly in the SQL Playground.

Notes

I learned that SQL keywords are not case-sensitive, but using uppercase for SQL commands is a common convention and improves query readability.

Next step

Continue practicing "SELECT" queries before moving on to other SQL concepts.
