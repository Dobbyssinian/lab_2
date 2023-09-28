# Linux CLI (*Week4_lab*)

Popular distributions include Debian, Fedora, and Ubuntu, among many others.

Runs on CLI (Command Line Interface) (*Type directly on the keyboard to use it*)

---

## Run Shell Termianl
* Linux / MacOS: Runs on “Terminal”
* Windows: Runs on ”Git Bash”
  


## Difference between CLI and GUI
* **CLI(Command Line Interface)**
> 1. Have to remember commands</br>
> 2. Keyboards, mostly</br>
> 3. Relatively fast</br>
> 4. Scripts enable automation and records</br>
> 5. Basic environment for developers 

* **GUI(Graphical User Interface)**
> 1. Easy to use and Intuitive</br>
> 2. Mouse mostly + Some keyboard shorcuts</br>
> 3. Relatively slow</br>
> 4. Manual labors required for repetitive tasks</br>
> 5. For daily users</br>

</br>

# Shell command

***pwd(present Working Directory)*** : Show the current path
```sh
$ pwd
/c/Users/KDH
```

***ls(list)*** : Show directory and files in the current path
```sh
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
```
* options:
> -l show detailed information (long format) </br>
> -lh same as above, but size in units <br>


***cd(chage directory)*** : Chage working diectory

* arguments:

> / (root)</br>
> . (current directory)</br>
> .. (upper-level directory) </br>
> ~ (home of current user) </br>
> /\[directory name]: absolute path </br>
> /\[directory name]: relative path </br>
> ../\[directory name]: relative path </br>


## Tip
***Autocompletion***

Press the "TAB" then command will complete automaticaly.

***Past commands***

Press the "UP Arrow" 

***clear***

type "clear" in the shell, the shell will be clean

</br>

## Manupulation
* ***cp(copy)*** : copy files and directories
* ***mv(move)*** : move files and directories or rename them
* ***rm(remove)*** : delete files and directories
* ***mkdir(make dirctory)*** : make a new directory

</br>

## Other command
* ***help (command)*** : Explan how to use the command (ex. cd, ls, rm, etc.)
* ***exit*** : Exiting terminal

