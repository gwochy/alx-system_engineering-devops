su betty // this script changes or switches users

whoami // prints the effective user name of the current user

groups // this script prints all the groups the current user is part of

sudo chown you filename // changes owner to a new owner of the file

touchfilename //this script create an empty file

chmod u+x filename // this script gives executing permission on a named file

chmod ug+x o+r filename // this script gives execution rights to both user and groug and reading rights to others

chmod ugo+x filename //this script gives execution permission to everybody

chmod 007 filename // this gives only the other users al the permissions but not the owner and the group users

chmod 753 filename // owner all rights, group read and execute, others write and execute

chmod --reference=olleh hello // this script mirrors the permissions in one file into another

chmod -R +111 */  //this script adds execution permissions to all subfolders in the current directory

mkdir -m 751 my_dir // this script creates a directory my_dir with 751 permissions

chgrp school hello //the script changes the grou owner

chown vicent:staff * // changes owner to vicent and group to staff for all files and directories

chown -h vicent:staff _hello // changes both the owner and group owner of _hello to vicent and staff respectively

telnet towel.blinkenlights.nl // this script plays the starwars iv episode in the terminal


