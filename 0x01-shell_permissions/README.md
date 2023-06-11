## Shell Permissions
In this project, I learnt about linux file permissions, how to change permissions, owner and group of a file, how to run a command with root privileges etc.
## Tasks :page_with_curl:
* **0. My name is Betty**

  * [0-I am Betty](0-iam_betty): Bash script that switches the current user to the user `betty`.

* **1. Who am I**

  * [1-Who am i](1-who_am_i): Bash script that displays the effective username of the current user.

* **2. Groups**

  * [2-Groups](2-groups): Bash script that displays all the groups the current user is part o

* **3. New owner**

  * [3-New Owner](3-new_owner): Bash script that changes the owner of the file `hello` to the user `betty`.
  .
* **4. Empty!**

  * [4-Empty](4-empty): Bash script that creates an empty file called `hello`.

* **5. Execute**

  * [5-Execute](5-execute): Bash script that adds execute permission to the owner of the file `hello`.

* **6. Multiple permissions**

  * [6-Multiple permissions](6-multiple_permissions): Bash script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

* **7. Everybody!**

  * [7-Everybody](7-everybody): Bash script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.

* **8. James Bond**

  * [8-James Bond](8-firstdelete): Bash script that sets the permission to the file `hello` as follows:

  * Owner: no permission at all

  * Group: no permission at all

  * Other users: all the permissions

* **9. John Doe**

  * [9-John Doe](9-John_Doe): Bash script that sets the mode of the file hello to this:

  `-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`

* **10. Look in the mirror**

  * [10-Mirror Permissions](10-mirror_permissions): Bash script that sets the mode of the file `hello` the same as `olleh’s` mode.

* **11. Directories**

  * [11-Directories Permissions](11-directories_permissions): Bash script that adds execute permission to all subdirectories of the *current directory* for the owner, the group owner and all other users.

* **12. More directories**

  * [12-Directories Permissions](12-directory_permissions): Bash script that creates a directory called `my_dir` with permissions *751* in the working directory.

* **13. Change group**

  * [13-Change Group](13-change_group): Bash script that changes the group owner to `school` for the file `hello`.

* **14. Owner and group**

  * [100-Change Owner and Group](100-change_owner_and_group): Bash script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

* **15. Symbolic links**

  * [101-Symbolic Link Permissions](101-symbolic_link_permissions): Bash script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively.

* **16. If only**

  * [101-If Only](102-if_only): Bash script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.

* **17. Star Wars**

  * [103-Star Wars](103-Star_Wars): Bash script that plays the StarWars IV episode in the terminal.
