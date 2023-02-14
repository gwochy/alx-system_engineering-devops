echo "Hello, World" # this prints Hello, World to standard output

echo "\"(Ôo)'" # this displays a confused smiley

cat /etc/passwd # this displays the content of /etc/passwd file

cat /etc/passwd /etc/hosts # this displays both contents of files /etc/passwd and /etc/hosts

tail /etc/passwd # this displays the last 10 lines in the file /etc/passwd

head /etc/passwd # this displays the first 10 lines of the file etc/passwd

head -3 iacta | tail -1 # this displays only the 3rd line from the file iacta

echo "Best School" >> file-name # this puts the words in quotes in the file given

escaping special characters # my goodness

ls -la > file-name # this overwrites and creates a file-name

tail -1 iacta >> iacta # this duplicates the last line of file iacta

find . -type f -name "*.js" -delete # this deletes any files ending in .js

find . -type d ! -path . | wc -l # this counts the number of directories and subdirectories in the current working directory

ls -t . | head #this displays the 10 newest files and begins with the newest to the oldest

sort | uniq -u # this one sorts and only print the unique word per line

grep  -i "root" /etc/passwd # this script displays lines containing 'root' patterns

grep -i "bin" /etc/passwd | wc -l # this script displays the number of lines with a 'bin pattern'

grep -iA 3 "root" /etc/passwd #displays line containing pattern root and the first 3 lines after it

grep -v "bin" /etc/passwd #displays all lines in the file that do not contain the pattern bin

grep -i '^[a-z]' /etc/ssh/sshd_config #displays all lines starting with a letter

tr 'Ac' 'Ze' #this replaces all Ac to Ze

tr -d cC #this removes all c and C from the file

rev #script that reverses input

cut -d ":" -f1,6 /etc/passwd | sort # displays all users and their home directories

find . -empty |rev | cut -d "/" -f 1 |rev # this finds all empty files and directories

find -type f -name "*.gif" -printf "%f\n" | rev | cut -d '.' -f 2- | rev | LC_ALL=C sort -f # lists all file with .gif and other conditions

find -type f -name "*.gif" -printf "%f\n" | rev | cut -d '.' -f 2- | rev | LC_ALL=C sort -f # lists all file with .gif and other conditions 

echo $(cut -c 1 | tr -d " \n") #ACROSTICS


tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -11 | rev | cut -d ' ' -f -1 | rev
