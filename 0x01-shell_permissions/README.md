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
