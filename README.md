# 0x16. C - Simple Shell

Write a simple UNIX command interpreter.

## Contributors

* Esraa Abdallah
* Tewodros Muche

## Project Files

*`AUTHORS`*
          file lists the contributors to the project.

*`README.md`*
         a brief overview of the project.

*`shell.h`*
         the header file which contains the standared header file and prototype of o function used in the program.

*`_atoi.c`*
         This file contains the implementation of functions that convert a string to an integer.
         
*`getenv.c`*
         This file contains the implementation of functions that retrieves the value of an environment variable.
 
*`parser.c`*
         This file contains the implementation of functions for parsing user input into arguments.

*`main.c`*
         initialize the program with infinite loop by call the prompt function.
         
## Compilation

+ Your shell will be compiled this way

> gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

+ run the shell using

> ./hsh
