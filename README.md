<a name="goback">

# Sweet Libs Team: James & Naomi
## Language: Bash Linux CLI

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


</a>
<a name="additional-resources">

## ADDITIONAL RESOURCES:


</a>

[Go Back to Table of Contents](#goback)

 
