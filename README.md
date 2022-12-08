<h1>0x16. C - Simple Shell</h1>
<h4>This repository contains the files for a simple_shell project. It can be compiled using GCC and will execute a simple shell that can be used for some basic tasks and programs most commonly found in the /bin/ folder.</h4>

<h3>Pre-requisites</h3>
<h2>Authorized functions and macros:</h2>
<h4><ul>
<li>access (man 2 access)</li>
<li>chdir (man 2 chdir)</li>
<li>close (man 2 close)</li>
<li>closedir (man 3 closedir)</li>
<li>execve (man 2 execve)</li>
<li>exit (man 3 exit)</li>
<li>_exit (man 2 _exit)</li>
<li>fflush (man 3 fflush)</li>
<li>fork (man 2 fork)</li>
<li>free (man 3 free)</li>
<li>getcwd (man 3 getcwd)</li>
<li>getline (man 3 getline)</li>
<li>getpid (man 2 getpid)</li>
<li>isatty (man 3 isatty)</li>
<li>kill (man 2 kill)</li>
<li>malloc (man 3 malloc)</li>
<li>open (man 2 open)</li>
<li>opendir (man 3 opendir)</li>
<li>perror (man 3 perror)</li>
<li>read (man 2 read)</li>
<li>readdir (man 3 readdir)</li>
<li>signal (man 2 signal)</li>
<li>stat (__xstat) (man 2 stat)</li>
<li>lstat (__lxstat) (man 2 lstat)</li>
<li>fstat (__fxstat) (man 2 fstat)</li>
<li>strtok (man 3 strtok)</li>
<li>wait (man 2 wait)</li>
<li>waitpid (man 2 waitpid)</li>
<li>wait3 (man 2 wait3)</li>
<li>wait4 (man 2 wait4)</li>
<li>write (man 2 write)</li>
</ul></h4>
<h2>Compilation</h2>
<h4>gcc -Wall -Werror -Wextra -pedantic *.c -o hsh</h4>

<h4>This wil compile all the '.c' files and change the output's name to 'hsh'.</h4>

<h2>Template to test output:</h2>

<h4>$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$</h4>

<h4><ul>
<li>After you clone this repository and compile the program with the command above, you will generate a file called hsh that can be executed by entering ./hsh in your shell.</li>

<li>The output after the program is executed should look something like this:</li>

$| Where you will get a prompt in the shape of a dollar sign so you can start typing commands into your shell. A good example of how it should execute is the command shown above were the user enters 'ls' and then gets a list of the directory contents.
</ul></h4>
<h2>Function Prototypes:</h2>
<h3>Brief description of functions contained in project:</h3>

<h4>_strcmpdir : compares strings to find dir. find_command : finds command to execute in path routes. charput : writes the character like putchar. place : similar to puts in C. _strlen : string length. str_concat : concatenate strings. lookforslash : identify if first char is a '/'. compareExit : checks if user typed exit. compareEnv : checks if user typed env. execute_proc : receives command and args from getline to be executed. identify_string : returns pointer with folder address. prompt : infinite loop with fork to keep prompt going. controlC: avoid program closing when pressing ctrl + c. main: initialize program.</h4>

<h2>Authors</h2>
<h3><ul>
<li>Theodorh | dorhtheophilus@gmail.com</li>
<li>Ken | ekrikakenny@gmail.com</li>
</ul></h3>
