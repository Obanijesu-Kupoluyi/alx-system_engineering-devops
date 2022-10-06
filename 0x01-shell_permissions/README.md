# SHELL PERMISSIONS
### Description
Hello fellow software engineers, this project is based on permitting files and directories, changing ownership of files and groups, swithching to another user, using superuser privileges, discovering the effective username of the current user and listing the name of groups that the current user is part of.
### Contents
* **0-iam_betty**: It switches the current user to the user betty
* **1-who_am_i**: It prints the effective username of the current user
* **2-groups**: It prints all the groups the current user is part of
* **3-new_owner**: It changes the owner of the file hello to the user betty
* **4-empty**: It creates an empty file called hello
* **5-execute**: It adds execute permission to the owner of the file hello
* **6-multiple_permissions**: It adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
* **7-everybody**: It adds execution permission to the owner, the group owner and the other users, to the file hello
* **8-James_Bond**: It sets the permission to the file hello; no permissions for the owner and group, all permissions for other users
* **9-John_Doe**: It sets the mode of the file hello to this: `-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`
* **10-mirror_permissions**: It sets the mode of the file hello the same as olleh’s mode
* **11-directories_permissions**: It adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
* **12-directory_permissions**: It creates a directory called my_dir with permissions 751 in the working directory
* **13-change_group**: It changes the group owner to school for the file hello
* **100-change_owner_and_group**: It  changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
* **101-symbolic_link_permissions**: It changes the owner and the group owner of _hello to vincent and staff respectively
* **102-if_only**: It changes the owner of the file hello to betty only if it is owned by the user guillaume
* **103-Star_Wars**: It plays the StarWars IV episode in the terminal.
