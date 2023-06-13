## Shell Redirections
In this project, I learnt how to redirect standard output to a file,get input from a file instead of a keyboard, send output from one program to another and also combine commands and filters with redirections.

## Tasks :page_with_curl:
* **0. Hello World**

  * [0-Hello World](0-hello_world): Bash script that prints `Hello, World`, followed by a new line to the standard output.

* **1. Confused smiley**

  * [1-Confused smiley](1-confused_smiley): Bash script that displays a confused smiley `"(Ôo)'`.

* **2. Let's display a file**

  * [2-Hellofile](2-hellofile): Bash script that display the content of the `/etc/passwd` file.

* **3. What about 2?**

  * [3-Two Files](3-twofiles): Bash script that display the content of `/etc/passwd` and `/etc/hosts`.
  .
* **4. Last lines of a file**

  * [4-Last Lines](4-lastlines): Bash script that display the last 10 lines of `/etc/passwd`.

* **5.  I'd prefer the first ones actually**

  * [5-First Lines](5-firstlines): Bash script that display the first 10 lines of` /etc/passwd`.

* **6. Line #2**

  * [6-Third Line](6-third_line): Bash script that displays the third line of the file `iacta`.

* **7.  It is a good file that cuts iron without making a noise**

  * [7-File](7-file): Bash script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.

* **8.  Save current state of directory**

  * [8-Cwd State](8-cwd_state): Bash script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.

* **9. Duplicate last line**

  * [9-Duplicate Last Line](9-duplicate_last_line): Bash script that  duplicates the last line of the file `iacta`.

* **10. No more javascript**

  * [10-No More Js](10-no_more_js): Bash script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.

* **11. Don't just count your directories, make your directories count**

  * [11-Directories](11-directories): Bash script that counts the number of directories and sub-directories in the current directory.

    * The current and parent directories should not be taken into account
    * Hidden directories should be counted

* **12. What’s new**

  * [12-Newest Files](12-newest_files): Bash script that displays the 10 newest files in the current directory.

    * Requirements:

      * One file per line

      * Sorted from the newest to the oldest

* **13. Being unique is better than being perfect**

  * [13-Unique](13-unique): Bash script that takes a list of words as input and prints only words that appear exactly once.

    * Words should be sorted

    * Input format: One line, one word

    * Output format: One line, one word

* **14. It must be in that file**

  * [14-Find That Word](14-findthatword): Bash script that display lines containing the pattern `root` from the file `/etc/passwd`.

* **15. Count that word**

  * [15-Count that word](15-countthatword): Bash script that display the number of lines that contain the pattern `bin` in the file `/etc/passwd`.

* **16. What's next?**

  * [16-What next](16-whatsnext): Bash script that display lines containing the pattern `root` and 3 lines after them in the file `/etc/passwd`.

* **17. I hate bins**

  * [17-Hide This Word](17-hidethisword): Bash script that display all the lines in the file `/etc/passwd` that do not contain the pattern `bin`.

* **18.  Letters only please**

  * [18-Letters only](18-letteronly): Bash script that display all lines of the file `/etc/ssh/sshd_config` starting with a letter.

* **19. A to Z**

  * [19-AZ](19-AZ): Bash script that  replace all characters `A` and `c` from input to `Z` and `e` respectively.

* **20.  Without C, you would live in hiago**

  * [20-Hiago](20-hiago): Bash script that  removes all letters `c` and `C` from input.

* **21.  esreveR**

  * [21-Reverse](21-reverse): Bash script that reverse its input.

* **22. DJ Cut Killer**

  * [22-Users and Homes](22-users_and_homes): Bash script that displays all users and their home directories, sorted by users.

    * Based on the the `/etc/passwd` file

* **23. Empty casks make the most noise**

  * [100-Empty Casks](100-empty_casks): Bash script that finds all empty files and directories in the current directory and all sub-directories.

    * Only the names of the files and directories should be displayed (not the entire path)

    * Hidden files should be listed

    * One file name per line

    * The listing should end with a new line

* **24. It must be in that file**

  * [101-Gifs](101-gifs): Bash script that lists all the files with a `.gif` extension in the current directory and all its sub-directories.

    * Hidden files should be listed

    * Only regular files (not directories) should be listed

    * The names of the files should be displayed without their extensions

    * The files should be sorted by byte values, but case-insensitive (file `aaa` should be listed before file `bbb`, file `.b` should be listed before file a, and file `Rona` should be listed after file `jay`)

    * One file name per line

    * The listing should end with a new line

* **25. Count that word**

  * [102-Acrostic](102-acrostic): Bash script that decodes acrostics that use the first letter of each line.

* **26. The biggest fan**

  * [103-The biggest fan](103-the_biggest_fan): Bash script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
  
    * Order by number of requests, most active host or IP at the top
