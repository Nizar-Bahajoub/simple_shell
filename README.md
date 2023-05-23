<h1 align="center">
   0x16. C -Simple Shell
</h1>

<p align="center">
   📄 🚀 
</p>

<p align="center">
  <strong>
    Description
  </strong>
</p>

<p align="center">
This project is a Milestone Project for the C code at ALX Africa Software Engineering, focusing on implementing a shell. </br>
The Gates of Shell is a project in the first trimester designed to enhance students' understanding of advanced concepts related to shell programming, including processes, system calls, bit manipulation, file management, and error handling. </br>
The shell is a straightforward UNIX command interpreter that emulates the functionalities of the simple shell (sh). </br>
The entire program was written in the C programming language.
</p>

## COPYRIGHT
Copyright (C) 2023 by [**Elmehdi ER.RAJI**](https://github.com/Mehdi-tech-alt) and [**Nizar Bahajoub**](https://github.com/Nizar-Bahajoub) </br>
All rights reserved

 ## Description :

This shell is implemented using the C programming language.
It takes inspiration from the Thompson Shell.


## Environment :

Our simple-shell project was developed and tested on Ubuntu 14.04 LTS.

## Features
* Presents a prompt and awaits user input for a command. Each command line is terminated  with a new line.
* Displays an error message and prompts again if an executable cannot be found.
* Manages errors effectively.
* Accommodates command lines with arguments.
* Manages the PATH environment variable.
* Supports the exit feature and tracks the exit status.
* Prevents the shell from terminating upon receiving a Ctrl-C signal.
* Handles command separators using the `;` symbol.
* Handling the command seperator `;`
* Processes logical operators `&&` and `||` .
* Handle variable replacements `$?`  (exit status) and `$$` (process ID).
* Recognizes and handles comments denoted by  `#`
* Supports a history feature to recall previous commands.
* Allows file input for executing commands.

## Builtins
Our simple-shell project has support for the following built-in commands:

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| exit [n]            | Exit the shell, with an optional exit status, n.                                          |
| env                 | Print the environment variables.                                                          |
| setenv [var][value] | Sets an environment variable and its corresponding value. If the variable exists.         |
| alias[name[='value]]| Reads aliases with the given name.                                                        |
| unsetenv [var]      | Remove an environment variable.                                                           |
| cd [dir]            | Change the directory.                                                                     |
| help [built-in]     | Read documentation for a built-in.                                                        |


 ## Installation : Getting HSH
 
Clone the below repository and compile the files into an executable using the GCC compiler.
```
https://github.com/Nizar-Bahajoub/simple_shell.git
```

### Basic usage :bulb:
- First, Fork this Repository [Learn how to fork repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).
- Then Clone [Learn how to clone ](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
- Create an executable by running the following command:
- `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
- From there, type in the following command and press your enter button.
- `./hsh`
- Final step: ENJOY!


## Contributors :
* [**Nizar Bahajoub**](https://github.com/Nizar-Bahajoub)
* [**Elmehdi ERRAJI**](https://github.com/Mehdi-tech-alt)

## Acknowledgments :
- The creators of the C language.
- Our software engineer-in-residence.
- Betty Holberton | Alx-Africa .
