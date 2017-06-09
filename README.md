<a name="goback">

# Sweet Libs Language: Bash Linux CLI
## Team: Naomi & James

</a>

### TABLE OF CONTENTS:

1. [Intro-and-history](#intro-and-history)
2. [Fun-Games](#fun-games)
3. [Hello-World](#hello-world)
4. [Commands-to-save](#commands-to-save)
5. [Additional-Resources](#additional-resources)

<a name="intro-and-history">

## INTRO AND HISTORY:

### What Is "The Shell"?

Simply put, the shell is a program that takes commands from the keyboard and gives them to the operating system to perform. In the old days, it was the only user interface available on a Unix-like system such as Linux. Nowadays, we have graphical user interfaces (GUIs) in addition to command line interfaces (CLIs) such as the shell.

On most Linux systems a program called bash (which stands for Bourne Again SHell, an enhanced version of the original Unix shell program, sh, written by Steve Bourne) acts as the shell program. Besides bash, there are other shell programs that can be installed in a Linux system. These include: ksh, tcsh and zsh. https://en.wikipedia.org/wiki/Stephen_R._Bourne
 
Bash is a unix based shell created by a programmer named Brian Fox while he worked for the Free Software Foundation. https://en.wikipedia.org/wiki/Brian_Fox_(computer_programmer)

### What's A "Terminal?"

It's a program called a terminal emulator. This is a program that opens a window and lets you interact with the shell. There are a bunch of different terminal emulators you can use. Most Linux distributions supply several, such as: gnome-terminal, konsole, xterm, rxvt, kvt, nxterm, and eterm.
 
While there are a number of different terminal emulators, they all do the same thing. They give you access to a shell session.

(http://linuxcommand.org/lc3_lts0010.php) 


</a>
<a name="fun-games">

## FUN GAMES:

### 1. TETRIS
- cd home
- type: emacs
- press enter to open
- press Esc
- type x
- type tetris
- play!

(this is what the shell script looks like to run this game: https://www.linuxquestions.org/questions/programming-9/tetris-game-based-on-a-shell-script-new-algorithm-911496-print/)


### 2. SNAKE:
- cd home
- type `emacs -q --no-splash -f snake`
 - play!
 
### 3. MAKE TERMINAL TALK:
- cd home
- type `say {words to talk}`
- hit enter
- make sure volume is turned on!
- have fun :)
 
### 4. WATCH STAR WARS:
- cd home
- type `telnet towel.blinkenlights.nl`
- hit enter
- enjoy!

### To exit emacs:
- hit esc 
- type control + x
- hit enter
- type ontrol + c
- hit enter

</a>
<a name="hello-world">

## HELLO WORLD:

### Step 1:

- Open your text editor and create a new plain text named `HelloWorld.sh`.

- In order to save as plain text using textEdit, go to format and change to: make plain text.

### Step 2:

- All scripts must begin with the shabang(#!) and since we are using bash, line 1 will look like this.

- `#!/bin/bash`

- Add the following code under the shebang line

- greeting=Hello\ World
function greet {
echo $greeting
}
greet

- Save your `HelloWorld.sh` file.

### Step 3:

- In order to run your script you will need to compile it first.

- Open your terminal and point the terminal to the folder that is holding the `HelloWorld.sh` file. 

- If you saved `HelloWorld.sh` to your documents folder you would type:

- `cd ~/documents`

### Step 4:

- In order to compile your script, inside the folder holding the `HelloWord.sh` file type:

- `chmod +x ./HelloWorld.sh`

### Step 5:

- After everything is done you can type:

- `./HelloWorld.sh`

- and you get a response of "Hello World"!


</a>
<a name="commands-to-save">

## COMMANDS-TO-SAVE:

NOTE: Most commands operate like this:

   `` command -options arguments ``

`Command` is the name of the command,
`-options` is one or more adjustments to the command's behavior,
`arguments` is one or more "things" upon which the command operates

- `pwd` = print working directory
- `cd` = change directory
- `ls` = list the files in the working directory
- `ls /bin` = list the files in the /bin directory
- `ls -l` = list the files in the working directory in long format 
- `ls -lah` = List all files with permissions
- `cp` = copy files and directories
- `mv` = move or rename files and directories
- `rm` = remove files and directories
- `mkdir` = create directories

</a>
<a name="additional-resources">

## ADDITIONAL RESOURCES:

- https://computers.tutsplus.com/tutorials/40-terminal-tips-and-tricks-you-never-thought-you-needed--mac-51192

- http://linuxcommand.org/lc3_learning_the_shell.php
 
- http://ryanstutorials.net/linuxtutorial/
 
- https://medium.freecodecamp.com/writing-command-line-applications-in-nodejs-2cf8327eee2 
 
- http://www.learnshell.org/ 


</a>

[Go Back to Table of Contents](#goback)
