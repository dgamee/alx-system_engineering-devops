## Learn shell basic
In this project, I learnt about basic shell commands, shell navigation, manipulation of files and how to use options and arguments with commands.
## Tasks :page_with_curl:
* **0. Where am I?**

  * [0-Current Working Directory](0-current_working_directory): Bash script that displays the absolute path name of the current working directory.

* **1. What's in there?**

  * [1-List it](1-listit): Bash script that displays the contents list of your current directory.

* **2. There is no place like home**

  * [2-Bring Me Home](2-bring_me_home): Bash script that changes the working directory to the user's home directory.

* **3. The long format**

  * [3-List Files](3-listfiles): Bash script that displays current directory contents in a long format
  .
* **4. Hidden files**

  * [4-List More Files](4-listmorefiles): Bash script that displays current directory contents, including hidden files using the long format.

* **5. I love numbers**

  * [5-List files digit only](5-listfilesdigitonly): Bash script that displays current directory contents in a long format with user and group IDs displayed numerically and hidden files

* **6. Welcome**

  * [6-First Directory](6-firstdirectory): Bash script that creates a directory named `my_first_directory` in the `/tmp/` directory.

* **7. Betty in my first directory**

  * [7-Move that file](7-movethatfile): Bash script that move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

* **8. Bye bye Betty**

  * [8-First Delete](8-firstdelete): Bash script that delete the file `betty`

* **9. Bye bye My first directory**

  * [9-First Dir Deletion](9-firstdirdeletion): Bash script that delete the directory `my_first_directory` that is in the `/tmp` directory.

* **10. Back to the future**

  * [10-back](10-back): Bash script that changes the working directory to the previous one.

* **11. File type**

  * [11-Lists](11-lists): Bash script that that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.

* **12. File type**

  * [12-File Type](12-file_type): Bash script that prints the type of the file named `iamafile`.

* **13. We are symbols, and inhabit symbols**

  * [13-Symbolic Link](13-symbolic_link): Bash script that create a symbolic link to`/bin/ls`, named  `__ls__`.

* **14. Copy HTML files**

  * [14-Copy Html](14-copy_html): Bash script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

* **15. Let’s move**

  * [100-Lets Move](100-lets_move): Bash script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.

* **16. Clean Emacs**

  * [101-Clean Emacs](101-clean_emacs): Bash script that deletes all files in the current working directory that end with the character `~`.

* **17. Tree**

  * [102-Tree](102-tree): Bash script that creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory

* **18. Life is a series of commas, not periods**

  * [103-commas](103-commas): Bash script that lists all the files and directories of the current directory, separated by commas (`,`).

  * Directory names end with a slash (`/`).

  * Hidden files and directories are listed.

  * The listing are alpha ordered, except for the directories `.` and `..` which are listed at the very beginning.

  * Only digits and letters are used to sort; Digits come first.

  * The listing end with a new line
