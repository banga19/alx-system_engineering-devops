This README is going to explain what the peoject is about

file 0-iam_betty: script switches the current user to the user {betty}

file 1-who_am_i: script prints effective username of the current user

file 2-groups: script prints all the groups the current user is part of

file 3-new_owner: script changes the owner of the file `hello` to `betty`

file 4-empty: script creates an empty file called `hello`

file 5-execute: script adds execute permissions to the owner of the file `hello` found in the working directory

file 6-multiple_permissions: script adds execute permissions to the owner and the group owner, and read permissions to other users, to the file `hello` , found in the working directory

file 7-everybody: script adds execution permission to the owner, the group owner and the other users, to the file `hello`,found in the working directory

file 8-James_Bond: script sets permissions to the file `hello` where: owner; has no permissions at all, Group; no permission at all, OtherUsers, all the permissions

file 9-John_Doe: scripts sets the mode of the file `hello` to the format --> `` -rwxr-x-wx 1 julien julien date/time filename{hello} ``

file 10-mirror_permissions: script sets the mode of the file `hello` the same as `olleh`. Both files are in the current working directory

file 11-directories_permissions: script will add execute permissions to all subdirectories of the current directory for the owner, the group and all other users. Regular files should not be changed

file 12-directory_permissions: script creates a directory called `my_dir` with permissions 751 in the working directory

file 13-change_group: script changes the group owner to `school` for the file `hello` in the working directory

file 100_change_owner_and_group: script changes the owner `vincent` and the group owner to `staff` for all the files and directories in the working directory

file 101-symbolic_link_permissions: script changes the owner and the group owner of `_hello` to `vincent` and staff respectively.

file 102-if_only: script changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`

file 103-Star_Wars: script will play star wars IV episode on the terminal

