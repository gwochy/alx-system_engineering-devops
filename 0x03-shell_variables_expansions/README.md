alis ls="rm *"  #this script creates an alias of ls

echo "hello $USER" #this script print hello and the current linux user

PATH=$PATH:/action # This adds directory /action to PATH

echo $PATH | tr ":" "\n" | wc -l # counts the number of directories in the PATH

printenv #this prints environment or global variables

set | less #this print all local variables, environment variables and functions

BEST="School" # this creates a new local variable

export BEST="School" #this script creates a new global variable

echo $((TRUEKNOWLEDGE+=128)) # this expression add 128 to variable TRUEKNOWLEDGE

echo $((POWER/DIVIDE)) # Divides POWER by DIVIDE

echo $((BREATH**LOVE)) #this return the of breath being powered by love

echo "$((2#BINARY))" # this converts binary base to a decimal base

echo {a..z}{a..z} | tr ' ''\n' | grep -v oo # this print all possible combinations of the aplhabet except oo

printf "%.2f\n" $NUM #this returns a float NUM with two decimal places

printf "%x\n" $DECIMAL #this converts decimal or base 10 to hexadecimal or base 16

sed -n 'p:n' #print every other line or every 3rd line or odd number line
