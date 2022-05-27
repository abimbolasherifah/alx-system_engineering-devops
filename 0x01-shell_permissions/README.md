0.su betty :script that switches the current user to the user betty.
1.whoami :script that prints the effective username of the current user.
2.groups:script that prints all the groups the current user is part of
3.chown betty hello:script that changes the owner of the file hello to the user betty.
4.touch hello:a script that creates a new file
5.chmod u+x hello:Write a script that adds execute permission to the owner of the file hello . Hello is on the working directory. 
6.chmod ug+x,r+o hello: script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
The file hello will be in the working directory
7.chmod a+x hello: a script that adds execution permission to the owner, the group owner and the other users, to the file hello
8.chmod 007 hello:Write a script that sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
9.chmod 753 hello :script that sets the mode of the file hello to -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10.chmod --reference=olleh hello :script that sets the mode of the file hello the same as olleh’s mode.
11.a+X * : a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
12.mkdir -m 751 my_dir :script that creates a directory called my_dir with permissions 751 in the working directory
13.chgrp school hello :script that changes the group owner to school for the file hello
14.sudo chown vincent:staff ./* : script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
15. chown -h vincent:staff _hello :script that changes the owner and the group owner of _hello to vincent and staff respectively.
The file _hello is in the working directory.The file _hello is a symbolic link
16. chown --from=guillaume betty hello : script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
The file hello will be in the working directory
17. telnet towel.blinkenlights.nl :script that  plays the StarWars IV episode in the terminal.
