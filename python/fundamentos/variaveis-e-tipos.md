Python — Fundamentos

🇧🇷 Português

Conteúdos estudados

Até este momento, estudei os seguintes fundamentos de Python:

- Variáveis e atribuição
- Regras para nomes de variáveis
- Case sensitivity
- Tipos de dados:
  - "int"
  - "float"
  - "str"
  - "bool"
- Tipagem dinâmica
- "print()"
- "type()"
- "isinstance()"
- Operadores aritméticos

Prática realizada

Pratiquei os conceitos por meio de exercícios envolvendo:

- criação e atribuição de variáveis;
- identificação de tipos de dados;
- utilização de "print()";
- utilização de "type()";
- utilização de "isinstance()";
- operações matemáticas básicas.

---

Prática de revisão — Variáveis, tipos de dados e funções básicas

Nesta sessão, revisei e pratiquei conceitos relacionados a variáveis, tipos de dados, funções e saída no terminal.

Como já havia estudado Python anteriormente, esta sessão teve como objetivo reforçar fundamentos e registrar uma prática realizada durante meus estudos.

1. Variáveis e atribuição

Revisei a estrutura básica de atribuição de uma variável:

name = 'Alice'

Nesse exemplo, "name" é a variável que recebe o valor "'Alice'".

2. Tipo "str"

O valor "'Alice'" é do tipo "str", utilizado para representar uma sequência de caracteres.

Também pratiquei a identificação do tipo de uma variável utilizando "type()":

type(name)

O resultado é:

<class 'str'>

3. Função "print()"

Revisei o uso de "print()" para exibir valores no terminal:

print(name)

Nesse caso, o conteúdo armazenado na variável "name" é exibido.

4. Aninhamento de funções

Também pratiquei a utilização do resultado de uma função como argumento para outra:

print(type(name))

Nesse exemplo, "type(name)" é avaliado e seu resultado é passado para "print()".

Isso permite visualizar diretamente o tipo da variável no terminal.

5. Sintaxe e indentação

Revisei também a importância da indentação em Python.

O Python utiliza espaços no início das linhas para representar a estrutura do código. Uma indentação incorreta ou desnecessária pode gerar erros como:

IndentationError

Código praticado

name = 'Alice'

print(name)

print(type(name))

Resultado esperado

Alice
<class 'str'>

O que reforcei com esta prática

- atribuição de valores a variáveis;
- utilização do tipo "str";
- identificação de tipos com "type()";
- utilização de "print()";
- passagem de argumentos para funções;
- aninhamento de funções;
- importância da indentação na sintaxe do Python.

Observação

Esta prática faz parte da minha revisão e consolidação dos fundamentos de Python.

O objetivo deste registro é acompanhar minha evolução e manter evidências das práticas realizadas durante os estudos.

---

🇺🇸 English

Topics studied

So far, I have studied the following Python fundamentals:

- Variables and assignment
- Variable naming rules
- Case sensitivity
- Data types:
  - "int"
  - "float"
  - "str"
  - "bool"
- Dynamic typing
- "print()"
- "type()"
- "isinstance()"
- Arithmetic operators

Practice

I practiced these concepts through exercises involving:

- creating and assigning variables;
- identifying data types;
- using "print()";
- using "type()";
- using "isinstance()";
- performing basic mathematical operations.

---

Review Practice — Variables, Data Types, and Basic Functions

In this session, I reviewed and practiced concepts related to variables, data types, functions, and terminal output.

Since I had already studied Python before, this session was focused on reinforcing fundamentals and documenting a practice session completed during my studies.

1. Variables and assignment

I reviewed the basic variable assignment syntax:

name = 'Alice'

In this example, "name" is the variable that receives the value "'Alice'".

2. "str" type

The value "'Alice'" has the "str" type, which is used to represent a sequence of characters.

I also practiced identifying the type of a variable using "type()":

type(name)

The result is:

<class 'str'>

3. "print()" function

I reviewed how to use "print()" to display values in the terminal:

print(name)

In this case, the content stored in the "name" variable is displayed.

4. Function nesting

I also practiced using the result of one function as an argument for another:

print(type(name))

In this example, "type(name)" is evaluated and its result is passed to "print()".

This makes it possible to display the variable's type directly in the terminal.

5. Syntax and indentation

I also reviewed the importance of indentation in Python.

Python uses spaces at the beginning of lines to represent code structure. Incorrect or unnecessary indentation can generate errors such as:

IndentationError

Practiced code

name = 'Alice'

print(name)

print(type(name))

Expected output

Alice
<class 'str'>

What I reinforced with this practice

- assigning values to variables;
- using the "str" type;
- identifying types with "type()";
- using "print()";
- passing arguments to functions;
- nesting functions;
- understanding the importance of indentation in Python syntax.

Note

This practice is part of my Python fundamentals review and consolidation.

The purpose of this record is to track my progress and maintain evidence of the practices completed throughout my studies.

Variáveis e tipos de dados em Python

🇧🇷 Português

O que aprendi

Neste exercício, pratiquei a criação de variáveis em Python e a identificação dos tipos de dados armazenados nelas.

Trabalhei com:

- "str" — texto
- "bool" — valores booleanos ("True" e "False")
- "int" — números inteiros
- "float" — números decimais

Exemplo

name = 'Alice'
print(name, type(name))

is_student = True
print(is_student, type(is_student))

age = 20
print(age, type(age))

score = 80.5
print(isinstance(score, float))

print(score, type(score))

O que pratiquei

Usei "type()" para verificar o tipo de um valor:

print(type(name))

Também usei "isinstance()" para verificar se um valor pertence a determinado tipo:

print(isinstance(score, float))

Meu aprendizado

Aprendi que uma variável pode armazenar diferentes tipos de valores e que Python permite verificar o tipo desses valores durante a execução do programa.

Também pratiquei a diferença entre "type()" e "isinstance()".

Próximos passos

Continuar estudando os tipos de dados e praticar operações com eles.

---

🇺🇸 English

What I learned

In this exercise, I practiced creating variables in Python and identifying the types of data stored in them.

I worked with:

- "str" — text
- "bool" — boolean values ("True" and "False")
- "int" — integer numbers
- "float" — decimal numbers

Example

name = 'Alice'
print(name, type(name))

is_student = True
print(is_student, type(is_student))

age = 20
print(age, type(age))

score = 80.5
print(isinstance(score, float))

print(score, type(score))

What I practiced

I used "type()" to check the type of a value:

print(type(name))

I also used "isinstance()" to check whether a value belongs to a specific type:

print(isinstance(score, float))

What I learned

I learned that a variable can store different types of values and that Python allows us to check the type of these values during program execution.

I also practiced the difference between "type()" and "isinstance()".

Next steps

Continue studying data types and practice operations with them.
