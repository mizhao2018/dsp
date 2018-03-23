# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

| Command | Action                                                                |
|---------|:---------------------------------------------------------------------:|
| ls      | list the contents of a particular directory                           |
| ls -a   | list the contents including hidden files                              |
| ls -l   | long listing                                                          |
| ls -lh  | long listing with human readable file sizes                           |
| ls -lah | including hidden files with long listing in human readable file sizes |
| ls -t   | list content sorted                                                   |
| ls -Glp | long listing sorted                                                   |

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

'xargs' can run a particular command for every item in a list, think of bulk editing. 
Example: a list of .jpg files but some with caps and others not. Trying to put all of them to lower cases.
Step 1: List the items of interest _ls_
Step 2:
  * First, use command __basename__ to get the name with the suffix removed
  * __-s__ to specify what the suffix is that should be removed.
  * __-a__ if there are multiple of these files.
  * use __xargs__ 
  * type __-n1__ to specify that the command needs to work for every item that passes through the pipe.
  * __-i__ indicates that we will use a replacement string in the next command 
  * __mv__ is the command 


 

