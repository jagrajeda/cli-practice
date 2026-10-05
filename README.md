# Command Line Practice

## Points to Ponder

*Look through these now and then use them to test yourself after doing the assignment*

* What is the command line?
 ## the command line is a text based interface where there is no GUI, that can run programs, be used to navigate through directories and files,  and execute commands.

* How do you open it on your computer?
 ## On my MacBook Pro, nromally I'd press 'CMD' + 'Spacebar' to open up the spotlight and then type in Terminal and hitting the return key. However due to other applications running on my machine, this has been deisabled - Since I have installed VsCode I can also enter 'Control' + '~'

* How can you navigate into a particular file directory?
 ## by typing in cd followed by the desired path of where you want to navigate to.

    - Where will `cd .` navigate you to?
 ## this keeps you in the current folder or directory
    - Where will `cd ..` navigate you to?
 ## This will take you up one level to the parent folder or directory
    - Where will `cd ~` navigate you to?
 ## This takes you to the user home directory
    - Where will `cd /` navigate you to?
 ## this will take you to the root directory


* How can you display the name of the directory you are currently in?
 ## type in pwd and hit return

* How can you display the contents of the directory you are currently in?
 ## we can use the 'ls' or 'ls -a' the latter which shows hidden files

* How can you create a new directory?
 ## we can use the mkdir followed by the desired new folder/directory name like mkdir newdirectory

* How can you create a new file?
 ## we can use the 'touch' command so something like 'touch newfile.txt'

* How can you destroy a directory or file?
 ## very nervously by using the remove command 'rm', so like 'rm newfile.txt' which helps remove a file.  for a folder/directory more nervously by using the 'rmdir newdirectory'

* How can you rename a directory or file?
 ## this I think was by using the move command. so like 'mv newdirectory newerdirectory' or 'mv newfile.txt newerfile.txt'

## Assignment:

1. Complete this interactive course to get a great handle on the essentials of using a command-line interface and navigating directories - [Terminal Tutor](https://www.terminaltutor.com/)

2. Complete the below exercise locally on your own computer.

> Unlike Terminal Tutor, your own local terminal can autocomplete file names based on the directory you are in. For example, if you had a directory structure like:
> ```
> home
> |- essays
> |- documents
> |- doodles
> |- code
>```
> and you were currently at home (`~`) all you would need to type is `e` and then hit tab to autocomplete. If you typed `d` and hi tab it would list the two possible matching options (`documents`, `doodles`) prompting you to type enough for it to know for sure what you mean when you hit tab. Tab autocomplete is a powerful feature when navigating a filesystem through the terminal as it let's you know what is available at any given level and allows you to not have write out entire file/folder names completely. Try to take advantage of it!

## Exercise:

In this exercise you will practice creating files and directories and deleting them.

1. Navigate to your home directory (`~`)
1. Create a new directory in your home directory and  name it `test`
2. Navigate into the `test` directory
3. Create a new file called `test.txt` using the `touch` command
4. Open this file with VSCode (from the command line using `code test.txt`) give it some content, and then save
5. From within the cli, view the contents of the file you just created (`head`, `tail`, `less`)
4. Navigate one level up from the `test` directory to it's parent directory
5. Delete the `test` directory (it contains files now, so you might need to add an option to `rm`!)


## this is my edits to test that the readme file updates