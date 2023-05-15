# PREP: Practice in the Terminal

## The Command Line

> \> The Command Line is a text based interface to the system where the user enters commands using the keyboard and will get a response based on that command.All terminals have `shells` but the most commonly used one is `bash` which stands for *Bourne again shell*. run `echo $SHELL` to see what your current shell is.

## Basic Navigation

Navigation is an important part of using the command line. A lot of the things we do, such as cloning GitHub Repos or creating/delete files, depend on  being able to point to the correct location of a file or director. Here are a few code commands commonly used.

- `pwd` - **P**rint **W**orking **D**irectory - Outputs your currently location in the Terminal.
- `ls` - **L**i**s**t - lists out all the items in the current location. _You can list out items in a different different directory without navigating to that specific directory by typing the path after `ls` for example `ls /anotherFolder`_
- `cd` - **C**hange **D**irectory - Moves you from one directory to another. 

  ### Things to note
    - `~` = shortcut to the home directory
    - `./` = refers to all things in the current directory
    - `../` referes to all things in the parent directory (Add on extra `../` to move up an additional level)

## More About Files

In Linux, EVERYTHING is a file. If we want to know what type of file something is, we just need to type `file [path name]`. For example, if I ran the `file projects` on my projects folder, the terminal will output `projects: directory`. 

  ### Things to note
  - Linux is Case Sensitive: Projects != projects
  - Spaces in names:
    - Spaces in file/directory names are fine but when using the command line to navigate to a file or directory that _has_ a space, we must use quotes around the file name or use the backslash `'\'` so that the CL can interpret where we want to go for example: File Name.txt = `'File Name.txt'` or `File\ Name.txt`
  - To list out all files in a directory including those that are hidded, use `-a` after the list command eg `ls -a`.


## Manual Pages

Manual pages are a set of pages that document what a command is, it's purpose, and its use. to look up a specific command you would type out  `'man [comnmand to look up]'` for example `'man ls'`. Manual pages can also be searched using keywords `'man -k [search term]'`.

## File Manipulation

File manipulation covers all the things we can do in the file explorer but from the command line. these include Creating, deleting, renaming, and moving folders and files.


    - mkdir <directory name> - Creates a directory
    - rmdir <directory> - removes a directory
    - cp <source> <destination> - copies a file (source) and creates a new file (destination)
    - cp -r <source> <file> - Recursive copy that allows us to create copies of a directory.
    - mv <source> <destination> - move items or directories into another directory. the `mv` command can also be used to rename files 
    - rm <file name> - deletes a file
    - rm -r <directory> - removes a non-empty directory.

