su betty - switches the current user to the user betty.
whoami - prints the effective username of the current user.
groups - prints all the groups the current user is part of.
chown betty hello - changes the owner of the file hello to the user betty
touch hello - creates an empty file called hello.
chmod u+x hello - adds execute permission to the owner of the file hello.
chmod u+x,g+x,o+r hello - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod a+x hello - adds execution permission to the owner, the group owner and the other users, to file hello
chmod 007 hello - sets permissions to files.
chmod 753 hello - sets the mode of the file hello
chmod --reference=olleh hello - sets mode of the file hello the same as olle's mode
chmod -R a+x */ - adds execute permission to all subdirectories of the current directory for the owner, the roup owner and all other users
mkdir -m 751 my_dir - creates a directory called my_dir with permissions 751 in the working directory
chgrp school hello - changes the group owner to school for the file hello
chown vincent:staff * - changes the woner to vincent and the group owner to staff for all the files and directories in the working directory.
