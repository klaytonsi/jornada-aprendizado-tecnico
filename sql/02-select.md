SQL SELECT — Selecionando todas as colunas

🇧🇷 Português

O que estudei

Nesta etapa, comecei a praticar o comando "SELECT" no SQL Playground.

Aprendi que uma das formas mais básicas de consultar uma tabela é utilizar:

SELECT * FROM users;

O caractere "*" representa todas as colunas da tabela.

Primeiro exercício

O primeiro exercício consistiu em selecionar todas as colunas da tabela "users":

SELECT * FROM users;

A consulta foi executada corretamente e retornou 8 registros.

Estrutura da consulta

A consulta possui duas partes principais:

SELECT *
FROM users;

- "SELECT" indica que quero consultar dados.
- "*" indica todas as colunas.
- "FROM" indica de qual tabela os dados serão obtidos.
- "users" é a tabela consultada.
- ";" finaliza a consulta.

Maiúsculas e minúsculas

Também pratiquei a mesma consulta utilizando as palavras-chave em letras minúsculas:

select * from users;

A consulta também funcionou.

Aprendi, portanto, que as palavras-chave SQL utilizadas nesse exercício não diferenciam maiúsculas de minúsculas.

Mesmo assim, o curso apresenta o uso de letras maiúsculas como uma convenção para facilitar a leitura das consultas:

SELECT * FROM users;

Quando utilizar "SELECT *"

Durante a prática, aprendi que "SELECT *" pode ser útil para:

- explorar uma tabela nova;
- visualizar rapidamente quais dados existem;
- realizar verificações rápidas;
- fazer consultas pontuais quando todas as informações são necessárias.

Também aprendi que, em código de produção, é preferível especificar exatamente as colunas necessárias em vez de utilizar "SELECT *".

Prática livre

O Playground também foi utilizado para experimentar diferentes situações.

Alguns testes propostos foram:

- esquecer o ponto e vírgula;
- utilizar um nome de tabela incorreto;
- verificar se é possível executar várias consultas simultaneamente.

Esses testes fazem parte da prática para observar o comportamento do ambiente SQL.

O que consolidei

Nesta etapa, pratiquei:

- "SELECT";
- "FROM";
- "*" como seleção de todas as colunas;
- execução de consultas no Playground;
- diferença entre maiúsculas e minúsculas nas palavras-chave SQL;
- uso do ponto e vírgula;
- importância de especificar colunas em consultas de produção.

Próximo passo

Continuar a prática de "SELECT", aprendendo a selecionar apenas as colunas necessárias em vez de utilizar "SELECT *".

---

🇺🇸 English

What I studied

In this stage, I started practicing the "SELECT" statement in the SQL Playground.

I learned that one of the most basic ways to query a table is:

SELECT * FROM users;

The "*" character represents all columns from the table.

First exercise

The first exercise was to select all columns from the "users" table:

SELECT * FROM users;

The query was executed successfully and returned 8 records.

Query structure

The query contains two main parts:

SELECT *
FROM users;

- "SELECT" indicates that I want to retrieve data.
- "*" represents all columns.
- "FROM" indicates which table the data comes from.
- "users" is the table being queried.
- ";" terminates the query.

Uppercase and lowercase

I also practiced the same query using lowercase SQL keywords:

select * from users;

The query worked as well.

I learned that the SQL keywords used in this exercise are not case-sensitive.

However, the course presents uppercase SQL keywords as a convention that improves query readability:

SELECT * FROM users;

When to use "SELECT *"

During the practice, I learned that "SELECT *" can be useful for:

- exploring a new table;
- quickly viewing the available data;
- performing quick data checks;
- one-off queries when all information is needed.

I also learned that in production code, it is better to specify exactly which columns are needed instead of using "SELECT *".

Free practice

I also used the Playground to experiment with different situations.

Some suggested tests were:

- forgetting the semicolon;
- using an incorrect table name;
- checking whether multiple queries can be executed at the same time.

These tests are part of the practice and help observe how the SQL environment behaves.

What I consolidated

In this stage, I practiced:

- "SELECT";
- "FROM";
- "*" for selecting all columns;
- executing queries in the Playground;
- case sensitivity of SQL keywords;
- the use of the semicolon;
- why specifying columns can be preferable in production queries.

Next step

Continue practicing "SELECT" by learning how to select only the columns that are needed instead of using "SELECT *".
