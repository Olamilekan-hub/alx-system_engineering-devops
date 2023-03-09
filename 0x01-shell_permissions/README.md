Shell Permissions

[0-iam_betty] - ```su betty``` This script change the user to betty when executed.

[1-who_am_i] - ```whoami``` THis script prints the username of the current user.

[2-groups] - ```groups``` This script prints the all groups the current user is  part of.

[3-new_owner] - ```sudo chown betty hello``` This script changes the owner of the file to betty.

[4-empty] - ```touch hello``` This script creates an empty file called hello when executed.

[5-execute] - ```chmod 744 hello``` This script adds the execute permission to the owner of the file hello.

[6-multiple_permissions] - ```chmod 754 hello``` This script adds the execute, read and write permission to the owner and group of the file hello.

[7-everybody] - ```chmod +x hello``` This script adds the execute permission to owners, groups and other users of the file hello.

[8-James_Bond] - ```chmod 007 hello``` This script gives full permission to other users and nothing to groups and owners.
