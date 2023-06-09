echo hello, World -- prints “Hello, World”, followed by a new line to the standard output.

echo \"\(Ôo\)\' -- displays a confused smiley "(Ôo)'.

cat /etc/passwd -- displays the content of the /etc/passwd file.

cat /etc/passwd /etc/hosts -- displays the content of /etc/passwd and /etc/hosts.

tail /etc/passwd -- displays the last 10 lines of /etc/passwd.

head /etc/passwd -- displays the first 10 lines of /etc/passwd.

head -n 3 iacta | tail -n 1 -- displays the third line of the file iacta.

echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)" -- creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

ls -la > filename -- writes into the file ls_cwd_content the result of the command ls -la and overwrites it if it still exists.

tail -n 1 iacta >> iacta -- duplicates the last line of the file iacta.

find . -type f -name "*.js" -delete -- deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

find -mindepth 1 -type d | wc -l -- counts the number of directories and sub-directories in the current directory.