simple shell project
# This projected was authored by Meaza and Samuel


The files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
Files will end with a new line
The codes will be checked using betty-style.pl and betty-doc.pl
The shell will not have any memory leaks
At most 5 functions will be created per file
All header files will include the guards
System calls will be used when needed

The shell terminal will do the following:
1. provides a prompt and wait for the user to type a command. A command line always ends with a new line.
	-The prompt is displayed again each time a command has been executed.
	-The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
	-The command lines are made only of one word. No arguments will be passed to programs.
	- If an executable cannot be found, print an error message and display the prompt again.
2. Handle command lines with arguments
3. Handle the PATH
4. Implement the exit built-in, that exits the shell
5.Implement the env built-in, that prints the current environment
6. Allow users to write their own getline functions
7. handle arguments for the built-in exit
8. Implement the setenv and unsetenv builtin commands
9. Implement the builtin command cd:
10. Handle the commands separator ;
11. Handle the && and || shell logical operators
12. Implement the alias builtin command
13. Handle variables replacement
14. Handle comments (#)
15. can take a file as a command line argument
