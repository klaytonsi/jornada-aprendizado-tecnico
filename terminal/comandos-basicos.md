Fundamentos de Terminal e Bash

🇧🇷 Português

O que estudei

Neste estudo, aprendi conceitos básicos relacionados ao uso de terminais e shells, principalmente em ambientes baseados em Unix/Linux.

Também pratiquei comandos básicos do Bash, atalhos de teclado e opções de comandos.

---

Terminal e Shell

Terminal

Um terminal é uma aplicação que oferece uma interface de linha de comando, permitindo executar comandos no sistema.

Shell

O shell é o software responsável por interpretar os comandos digitados na linha de comando.

Uma forma simples de diferenciar:

Terminal → interface onde interagimos
Shell    → interpreta os comandos

No Windows, o Windows Terminal permite acessar diferentes shells, como PowerShell e Command Prompt, dentro da mesma aplicação.

---

Atalhos importantes no Bash

Alguns atalhos estudados:

Atalho| Função
"Ctrl + L"| Limpa a tela
"Ctrl + Z"| Suspende o processo em primeiro plano
"!!"| Executa novamente o último comando

Exemplo

!!

Esse comando executa novamente o comando que foi executado anteriormente.

---

Comandos básicos

"pwd"

O comando "pwd" mostra o diretório de trabalho atual.

pwd

Pode ser entendido como:

"Em qual diretório eu estou?"

---

"touch"

O comando "touch" pode ser utilizado para criar um arquivo vazio quando ele ainda não existe.

touch notes.txt

Nesse caso, o arquivo criado é:

notes.txt

---

"mv"

O comando "mv" pode ser utilizado para mover ou renomear arquivos.

Por exemplo:

mv oldname.txt newname.txt

Nesse caso, o arquivo "oldname.txt" passa a se chamar "newname.txt".

---

Opções de comandos

Os comandos podem receber opções para alterar seu comportamento.

Short form

A forma curta normalmente utiliza um único hífen:

-a

Long form

A forma longa utiliza dois hífens:

--all

Uma diferença importante é:

-a       → short form
--all    → long form

Algumas opções curtas podem ser combinadas:

ls -ahs

Em situações apropriadas, isso permite utilizar várias opções em uma única sequência.

---

Opções com valores

Algumas opções podem receber valores.

Um exemplo estudado com "ls" é:

ls --color=auto

Nesse caso:

--color → opção
auto    → valor

A sintaxe utilizada é:

--option=value

---

Layout do teclado

Durante o estudo, também foi apresentada a recomendação de utilizar o layout English (US) em workshops de Bash e PostgreSQL.

Isso ocorre porque alguns caracteres especiais podem se comportar de maneira diferente dependendo do layout do teclado.

Um dos caracteres mencionados foi:

$

Portanto, se comandos não estiverem funcionando como esperado, uma das coisas que deve ser verificada é se o layout do teclado está configurado como English (US).

---

O que aprendi

Aprendi a diferença básica entre terminal e shell e comecei a entender como a linha de comando é utilizada.

Também pratiquei alguns comandos e conceitos importantes:

pwd       → diretório atual
touch     → criação de arquivo
mv        → mover/renomear
Ctrl + L  → limpar a tela
Ctrl + Z  → suspender processo
!!        → executar novamente o último comando
-a        → opção curta
--all     → opção longa

O principal aprendizado foi começar a entender que os comandos possuem uma estrutura e que as opções modificam seu comportamento.

---

O que ainda preciso estudar

Ainda preciso aprofundar meu conhecimento sobre:

- mais comandos do Bash;
- navegação pelo sistema de arquivos;
- permissões;
- processos;
- redirecionamento;
- pipes;
- variáveis de ambiente;
- scripts Bash.

---

🇺🇸 English

What I studied

In this study, I learned basic concepts related to terminals and shells, especially in Unix/Linux-based environments.

I also practiced basic Bash commands, keyboard shortcuts, command options, and keyboard layout considerations.

---

Terminal and Shell

Terminal

A terminal is an application that provides a command-line interface, allowing users to execute system commands.

Shell

A shell is the software responsible for interpreting commands entered through the command line.

A simple way to differentiate them is:

Terminal → interface we interact with
Shell    → interprets the commands

On Windows, Windows Terminal allows access to different shells, such as PowerShell and Command Prompt, from the same application.

---

Important Bash shortcuts

Some shortcuts studied:

Shortcut| Function
"Ctrl + L"| Clears the screen
"Ctrl + Z"| Suspends the foreground process
"!!"| Runs the last command again

Example

!!

This runs the command that was executed previously.

---

Basic commands

"pwd"

The "pwd" command prints the current working directory.

pwd

It can be understood as:

"Which directory am I currently in?"

---

"touch"

The "touch" command can be used to create an empty file when it does not already exist.

touch notes.txt

In this example, the created file is:

notes.txt

---

"mv"

The "mv" command can be used to move or rename files.

For example:

mv oldname.txt newname.txt

In this case, "oldname.txt" is renamed to "newname.txt".

---

Command options

Commands can receive options that change their behavior.

Short form

The short form normally uses a single hyphen:

-a

Long form

The long form uses two hyphens:

--all

An important difference is:

-a       → short form
--all    → long form

Some short options can be chained together:

ls -ahs

When appropriate, this allows multiple options to be used in a single sequence.

---

Options with values

Some options can receive values.

One example studied with "ls" is:

ls --color=auto

In this case:

--color → option
auto    → value

The syntax is:

--option=value

---

Keyboard layout

The study also presented the recommendation to use the English (US) keyboard layout in Bash and PostgreSQL workshops.

This is because some special characters may behave differently depending on the keyboard layout.

One of the characters specifically mentioned was:

$

Therefore, if commands are not working as expected, one of the things to check is whether the keyboard layout is configured as English (US).

---

What I learned

I learned the basic difference between a terminal and a shell and started to understand how the command line is used.

I also practiced several important commands and concepts:

pwd       → current directory
touch     → create a file
mv        → move/rename
Ctrl + L  → clear the screen
Ctrl + Z  → suspend a process
!!        → run the last command again
-a        → short option
--all     → long option

The main learning point was understanding that commands have a structure and that options can modify their behavior.

---

What I still need to study

I still need to study:

- more Bash commands;
- file system navigation;
- permissions;
- processes;
- redirection;
- pipes;
- environment variables;
- Bash scripting.
