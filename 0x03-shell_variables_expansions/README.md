alias ls="rm *" -- Create a script that creates an alias.
echo hello $USER -- prints hello user, where user is the current Linux user.export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/action -- Adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin| tr : n | wc -l -- counts the number of directories in the PATH.
printenv -- lists environment variables.
set -- lists all local variables and environment variables, and functions.
export BEST=School -- creates a new local variable.
export BEST=School -- creates a new global variable.echo 128 -- prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo -e $(($POWER/$DIVIDE)) -- prints the result of POWER divided by DIVIDE, followed by a new line.
echo $(($BREATH**$LOVE)) -- displays the result of BREATH to the power LOVE.echo 0 -- converts a number from base 2 to base 10.
echo {a..z}{a..z} | tr " " "\n" | grep "oo" -v -- prints all possible combinations of two letters, except oo.
printf "%.2f\n" $NUM -- prints a number with two decimal places, followed by a new line.
printf "%x\n" $DECIMAL -- converts a number from base 10 to base 16.
tr 'A-Za-z' 'N-ZA-Mn-za-m' -- encodes and decodes text using the rot13 encryption. Assume ASCII.
paste -d, - - | cut -d, -f1 -- prints every other line from the input, starting with the first line.