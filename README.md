Description
This repository contains the initial stage of a student project to build a clone of the AirBnB website. This stage implements a backend interface, or console, to manage program data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.


The command interpreter provides a simple REPL (Read-Evaluate-Print-Loop) for interacting with the models in this project only. It can be used to test the functionality of the supported storage engines as well. You can find some examples of its usage

First clone this repository.

Once the repository is cloned locate the "console.py" file and run it as follows:

➜  AirBnB_clone_v2 git:(master) ✗ ./console.py
When this command is run the following prompt should appear:

(hbnb)
This prompt designates that you are in the "HBnB" console. There are a variety of commands available within the console program.


Supported Commands
These are commands that can be executed by the command interpreter. They have the format command [argument]... but you could also use the format Model.command([argument]...), with the exception of the first 3 commands below.

Format


help [command]	Prints helpful information about a command (command). If command is not provided, it prints the help menu.
quit	Closes the command interpreter.
EOF

create Model [prop_key=prop_value]...




-Onyedibe Nakachukwu Sixtus
-james Chizurum Akandu Chizurum
