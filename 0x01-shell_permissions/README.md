su username - is used to switch the current user to another one
whoami command is used to print the effective username of the current user
groups is the command used to print all groups od the current user
chown newuser file - is used to change the owener of a file to another user
touch is used to dreate an empty file
chmod u+x filename is used to add execute permission to the owner of the file
*NB* Scripts on permissions are to be written using the symbolic form not the absolute form
script to add ececute to owner and group, and read to others is chmod u+x,g+x,o+r
using a single command ugo+x is the script to add execute functions to everyone ie user, gropu, others
At this point it is difficult to know when i should use the symbolic form or the absolute form. I am working with trial and error.
using absolute form chmod 007 filename is usedfor owner, group no prmission and others all permission
using octal notation ie absolute form chmod 753 filename is usedto derive -rwxr-x-wx the secret is to group them in threes from the left
