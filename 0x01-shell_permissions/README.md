#THIS IS README FOR SHELL PERMISSIONS
su betty or sudo betty switches user to betty
whoami prints the effective username of the current user
command 'group' displays all groups a user is part
sudo chown newuser file name -this command changes user to the new owner of file.
Touch filename creates an empty file.
To change user permission
To give x to ug and r to o chmod ug+x,o+r filename.
To write permission ug+0, o+rwx without using the comma just do chmod 007 filename.
To set permission rwxr-x-wx without use of comma chmod 753 filename
Write a script that sets the mode of the file hello to same as olleh' mode chmod --reference=olleh hello
: 0.00%)
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed. chmod a+X *
Create a script that creates a directory called my_dir with permissions 751 in the working directory. 
mkdir -m 751 my_dir
Write a script that changes the group owner to school for the file hello chgrp school hello
