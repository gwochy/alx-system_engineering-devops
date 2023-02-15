alis ls="rm *"  #this script creates an alias of ls

echo "hello $USER" #this script print hello and the current linux user

PATH=$PATH:/action # This adds directory /action to PATH

echo $PATH | tr ":" "\n" | wc -l # counts the number of directories in the PATH
