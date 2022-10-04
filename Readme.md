Shell Project

Finished the overall structure by adding the command line batch argument, and added help menu<br>

Objectives:<br><br>
Learn to work in groups to develop software using Git<br><br>

Gain experience developing multi-source file projects in C<br><br>

Experience using Makefiles and other software build tools<br><br><br>


Description:<br>
Design a simple command line shell and implement it on the specified UNIX platform
The Shell or Command Line Interpreter is the fundamental User interface to
an Operating System. The lab project is to write a simple shell - myshell -
that has the following functions:<br><br>

mycd - change working directory<br>
myclr - clear the screen<br>
mydir - list the contents of the directory<br>
myenviron - list all the environment string<br>
myecho - display the diaply followed by a new line<br>
myhelp - display the user manual using the more filter<br>
mypause - pause operation of the shell<br>
myquit - quit the shell<br><br>



Usage:<br>
The shell can be invoked on Windows command line interpreter by typing myshell. It can be invoked on a UNIX based OS<br>
by typing /myshell. The program accepts one argument which can be a batchfile containing user commands. <br>
For example: ./myshell commands.txt <br>
<br>

The following are the commands for the shell: <br><br>

myhelp :  Lists the help menu <br>
mydir "directory":  Lists the contents of the directory <br>
myenviron: Lists all the environment strings <br>
myecho "comment": Displays comment on the command line followed by a newline <br>
myclr. Clears the screen <br>
mycd "path": Changes the working directory to the specified path. <br>
mypause: Pauses operation of the shell until the ENTER key is hit <br>
myquit: Quits the shell <br>
