# DevOps Fundamentals - Linux Commands

Linux is the backbone of most DevOps environments. Understanding basic Linux commands is essential for managing servers, automation, and deployments.

Below are 30 important Linux commands every DevOps engineer should know, along with explanations and practical examples.

1. `pwd`(Print Working Directory): Prints the full path of the current working directory.

![alt text](images/print.PNG)

2. `ls` (List): Lists the contents of a directory. It shows files and folders in the current or specified directory. Options like -l (long format) and -a (all, including hidden files) are extremely common in DevOps workflows for auditing directory contents.

![alt text](images/ls.PNG)

3. `cd` (Change Directory): Changes the current working directory

![alt text](images/change.PNG)

4. `mkdir` (Make Directory): Creates one or more new directories. The -p flag allows creating nested directories in one command, even if the parent directories don't yet exist. 

![alt text](images/make.PNG)

5. `rm` (Remove): Removes files or directories. The -r flag enables recursive deletion (for directories), and -f forces deletion without prompting.

![alt text](images/remove.PNG)

6. `touch`: Creates an empty file or updates the timestamp of an existing file.

![alt text](images/touch.PNG)

7. `cp` (Copy): Copies files or directories from one location to another. The -r flag is required to copy directories recursively.

![alt text](images/copy.PNG)

8. `mv` (Move): Moves or renames files and directories. Unlike cp, the original is removed after the operation. 

![alt text](images/move.PNG)

9.`rmdir` (Remove Directory): Deletes an empty directory.

![alt text](<images/remove directory.PNG>)

10. `find`: Searches for files and directories within a directory tree based on conditions like name, type, size, permissions, or modification time. It's extremely powerful in DevOps for locating config files, finding large files consuming disk space, or identifying files that need permission changes.

![alt text](images/find1.PNG)

`.` in the above example means search in the current directory while `-name` means search by file name

![alt text](images/find2.PNG)

Where `-type d` = search for directories only, `-name "project"` = look for folder named project

11. `cat`: Concatenates and displays the contents of files. It can display one or multiple files, combine files together, or be used to quickly read short configuration files.

![alt text](images/cat.PNG)

12.  `less`: Allows page-by-page viewing of large files.  

![alt text](images/less.PNG)

13. `tail`: Outputs the last part of a file.

![alt text](images/tail.PNG)

14. `head`: Outputs the first part of a file. 

![alt text](images/head.PNG)

15. `echo`: Prints text to the terminal or writes to a file.

![alt text](images/echo.PNG)

In the below example, `echo` creates status.txt (if it doesn’t exist) then Writes the text inside it

![alt text](images/echo1.PNG)

`echo` is also used to append text in a file as shown in the example below.

![alt text](images/echo2.PNG)

`>` overwrites the file while `>>` adds to the end of the file






