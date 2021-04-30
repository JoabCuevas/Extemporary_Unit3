<center>
    <h1>Universidad Politécnica de Yucatán</h1>
</center>

-----

<!-- 
Markdown
![ImageLink](https://static.wixstatic.com/media/e16f80_9c4ca79ed84340e0984c64712e35448c~mv2_d_3000_2100_s_2.png) 
-->

<!-- HTML -->
<img src="https://static.wixstatic.com/media/e16f80_9c4ca79ed84340e0984c64712e35448c~mv2_d_3000_2100_s_2.png"> 

<center>
<h2>Assignature: Introduction to Algorithms</h2>

<h3>Name: Joab Abisai Cuevas Mendez</h3>

<h3>Teacher: Juan Vazquéz</h3>
</center>


Due date: 30/04/2021

-----

# Introduction
In this document I will describe the different commands that can be found and used in Git Bash in order to create, delete, save, etc., some document.


<center>
    <h1>Index</h1>
</center>

* mkdir
* rmdir / rm -r
* cp
* mv
* cd
* pwd
* diff
* cat
* grep
* echo
* nano
* vim
* cat + ">"
* history
* top
* whoami
  
  ----

  1. mkdir is a command from the UNIX, DOS, OS / 2, and Microsoft Windows operating systems used to create a new subdirectory or folder of the filesystem.
   Example: 
   ![Exm](src\Images\mkdir.PNG)

  2. rmdir and rm -r are commands that erase directories but the main difference is that rmdir is used to erase empty directories while rm -r can delete directories that are not empty.
   Example:
   ![Exm](src\Images\rm-r.PNG)
  
  3. The cp command in GNU / Linux is used to copy a file or folder working on the command line.
   Example:
   ![Exm](src\Images\cp.PNG)
  
  4. mv is a Unix command used to move or rename files or directories on the file system.
   Example:
   ![Exm](src\Images\mv.PNG)

  5. The chdir or cd command is a command used in DOS and UNIX operating systems to change the working directory.
   Example:
   ![Exm](src\Images\cd.PNG)

  6. The pwd command is used to print the name of the current directory in a command session under a Unix or derived operating system.
    Example:
    ![Exm](src\Images\pwd.PNG)

  7. The git diff command compares the differences between files line by line.
   Example:
   ![Exm](src\Images\gitdiff.PNG)

  8. The cat command in Linux is one of the most useful you can learn. It derives its name from the word concatenate and allows you to create, merge or print files to the standard output screen or to another file and much more.
   Example:
   ![Exm](src\Images\cat.PNG)

  9. Usually, grep takes a regular expression from the command line, reads the standard input or a list of files, and prints the lines that contain matches for the regular expression.
   Example:
   ![Exm](src\Images\grep.PNG)

  10. echo is a command for printing text on the screen.
   Example:
   ![Exm](src\Images\echo.PNG)

  11. nano is a minimalist and friendly text editor. However, not only does it allow us to edit text, but it also has other very interesting features that make it especially useful for modifying configuration files in the terminal, creating launchers, and all this type of action.
   Example:
   ![Exm](src\Images\nano.PNG)

  12. vim is an improved vi editor, and maybe some commands in vi don't work the same.
   Example:
   ![Exm](src\Images\vim.PNG)

  13. echo [text] > name is to write in a text file, and with two >> is to add another text.
   Example:
   1[Exm](src\Images\cat2.PNG)

  14. history is a very useful command to find out the last commands that have been executed on a Server.
   Example:
   ![Exm](src\Images\history.PNG)

  15. With top we will see an interface in text mode that will be updated every 3 seconds. It shows a summary of the state of our system and the list of processes that are running.
   Example:

   ![Exm](https://i.imgur.com/gqva3.jpg)

  16. whoami is a simple command, used to print the effective username of the current user when it is invoked, which is understood as the name of the user in session.
   Example:
   ![Exm](src\Images\whoami.PNG)

 -----

 ## Initial configuration

 * git config --global user.email joabcuevas@hotmail.com
 * git config --global user.name Joab_C

## Starting a project or cloning one

* git init name, to start a repository.
* git clone [link]

## Staging and commiting

* git add name, to add a new or modified file.
* git add ., to add all files.
* git commit -m name, to commit.
* git commit -am, to stage and commit at the same time.

## Pushing

* git push --set-upstream origin <branch>, to push a local branch for the first time.
* git config --global push.default **current**, to configure Git to always push using the current branch name.
* git push origin <local_branch>:<remote_branch>, to push a local branch to a different remote branch.

## Branches 

* git switch -c <new-branch-name>, to create and instantly change to that branch.
* git branch name, to create a new branch.
* git checkout name, to change to another branch.
* git branch -d name, to delete a branch.
* git branch --list, to see a list of all the branches of the repository.
 

 

 