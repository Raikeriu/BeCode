# Command Line Interface (CLI)  

## Navigation

#### Change directory 
````
cd
````

#### Use to list files and directories
````
ls
````

#### Shows you the full path of your current directory
````
pwd
````

#### Used to save the current directory into a stack and move to a new directory.
````
pushd
````

#### Used to return back to the previous directory that is on top of the stack.
````
popd
````

---

## File Operation

#### Print the content of a file
````
cat
````

#### Mainly used to create empty files and change timestamps of files or folders
````
touch
````

#### Creates directories
````
mkdir
````

#### Moves files and directories from one directory to another or renames a file or directory.
````
mv
````

#### Copies files from one location to another
````
cp
````

#### Used to delete files
````
rm
````

#### Used to delete empty directories
````
rmdir
````
#### used in searching and matching text files contained in the regular expressions.
````
grep
````
---

## Permissions

#### Modifies file permission
````
chmod [PERMISSION] FILE
````

#### Used to change the group ownership of a file or directory.
````
chgrp [GROUP_NAME] [DIRECTORY/FILE_NAME]
````

#### Used to change the file Owner or group.
````
chown [OWNER][:[GROUP]] FILE
````

#### Will run that command with elevated privileges.
````
sudo
````

#### Useful website for permissions explanations
````
https://www.howtogeek.com/437958/how-to-use-the-chmod-command-on-linux/
````

---

## Text Editor

#### User-friendly, free and open-source text editor that usually comes pre-installed in modern Linux systems.
````
nano FILE
````

#### a “modal” text editor based on the vi editor written by Bill Joy in the 1970s for a version of UNIX.
````
vim FILE
````

#### Cheat sheet for VIM
````
https://vim.rtorr.com
````

#### To input command in Vim
````
esc
````

---

## Environment variables

#### Allows you to display your current environment or run a specified command in a changed environment.
````
env
````

#### Displays the values of environment variables in the current shell.
````
printenv
````

#### Displays and sets the names and values of shell and Linux environment variables.
````
set
````

#### Delete the variables during program execution.
````
unset
````
#### Used to mark variables and functions to be passed to child processes.
````
export
````
#### A variable that has a default value is considered to be permanent
````
Permanent Variable
````

#### A temporary variable is a variable with short lifetime, usually to hold data that will soon be discarded, or before it can be placed at a more permanent memory location.
````
Temporary Variable
````

#### A script file that’s executed when a user logs in.
````
.bashrc
````
#### A website that can help explaining on how to create a permanent variable
````
https://devconnected.com/set-environment-variable-bash-how-to/
````
---

## Pipes and Redirections

#### The output redirection
````
 [OPTION] FILE1 > FILE2
 ````

 #### Standard error (also known as stderr) is the default error output device. Use stderr to write all system error messages.
 ````
 stderr
 ````

 #### Pipe is used to combine two or more commands
 ````
|
````
