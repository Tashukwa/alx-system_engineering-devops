alias ls="rm *" -- Create a script that creates an alias.
echo hello $USER -- prints hello user, where user is the current Linux user.export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/action -- Adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin| tr : n | wc -l -- counts the number of directories in the PATH.
