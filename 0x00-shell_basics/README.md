 pwd // prints the absolute path name of the current working directory

 ls // displays the content list of my current directory

 cd or cd \~ // changes working directory to user's home directory

 ls -l // displays current directory content in a long formatls

 ls -la // list all files including the hidden files in a long format

 ls -lna // list all files including hidden files with user and group id as numbers in a long format

  mkdir /tmp/my-first-directory // creates directory in the subdirectory of /tmp

 mv /tmp/betty /tmp/my-first-directory // moves the file betty to my-first-directoryfrom /tmp

 rm /tmp/my_first_directory/betty // deletesfile betty from my_first_directory

rm -r /tmp/my_first_directory // delecting a directory from /tmp directory

cd - // changes the working directory to a previous one

ls -al. .. /boot // lists all files in the working directory, parent directory and the /boot directory

file /tmp/iamafile // creating file type iamafile in /tmp

ln -s /bin/ls __ls__ // this creates a symbolic link to directory /bin/ls

cp -un*.html ../  // this copies all new html files to the parent directory

mv [[:upper:]]* /tmp/u // this moves all files starting with an upper case letter to /tmp/u directory

rm *~ // this deletes all files that end with a character ~

mkdir -p welcome/to/school // creates three directories in the working directory and the -p help add a trailing slash after each directory

ls -amvp // this list all files and directories, put commas with -m, sorts with v and -p helps give a trailing slash
