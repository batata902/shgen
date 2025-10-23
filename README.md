# SHGen 💀


SHGen is a Python tool that can generate web shells and reverse shells with a single command. It offers 70+ payloads written in a hundred programming languages, including Python, PHP, Java, Ruby, Haskell, Lua, C, shell scripts, and more.

Screenshot
----

![Screenshot](https://raw.githubusercontent.com/batata902/shgen/refs/heads/pictures/revshellsc.png)

List of all reverse shell payloads

Installation
----

You can download SHGen just cloning this github repository:

    git clone https://github.com/batata902/shgen.git

SHGen is written entirely in Python.

Usage
----

Before choosing your payload, you must specify the type of shell you want to generate (webshell or revshell).

    python3 shgen.py revshell

or

    python3 shgen.py webshell

Listing payloads options
----
After this you can list all payload options, for example:

    python3 shgen.py revshell --list

Output
![Output](https://raw.githubusercontent.com/batata902/shgen/refs/heads/pictures/revshellsc.png)

Print the generated code or save it to a file
----
If you type the -o argumment, SHGen will not print it in the screen. If -o argumment was not given, SHGen will print the code in the screen.

Example (no output file):

    python3 shgen.py revshell -s php-pentestmonkey --lhost 10.10.10.10 --lport 1234 

Output
![NoFileOutput](https://raw.githubusercontent.com/batata902/shgen/refs/heads/pictures/codeoutput.png)

----
Example (with output file):

    python3 shgen.py revshell -s php-pentestmonkey --lhost 10.10.10.10 --lport 1234 -o shell.php

Output
![FileOutput](https://raw.githubusercontent.com/batata902/shgen/refs/heads/pictures/fileoutput.png)

Special Thanks
----
Thanks to Messias Eric for the knowledge necessary for this simple project.
