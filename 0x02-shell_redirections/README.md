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

ls -1t | head -- displays the 10 newest files in the current directory.

sort | uniq -u -- takes a list of words as input and prints only words that appear exactly once.

grep root /etc/passwd -- displays lines containing the pattern “root” from the file /etc/passwd. 

grep "bin" /etc/passwd | wc -l -- displays the number of lines that contain the pattern “bin” in the file /etc/passwd.

grep -A 3 root /etc/passwd -- displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd. 

grep -v bin /etc/passwd -- displays all the lines in the file /etc/passwd that do not contain the pattern "bin".
grep ^[[:alpha:]] /etc/ssh/sshd_config -- displays all lines of the file /etc/ssh/sshd_config starting with a letter.
tr Ac Ze -- replaces all characters A and c from input to Z and e respectively. 
tr -d cC -- removes all the letters c and C frrom input.
rev -- reverses its input.
cut -d: -f1,6 /etc/passwd | sort -- displays all users and their home directories, sorted by users.
find -empty | cut -d: -f1 -- finds all empty files and directories in the current directory and all sub-directories. 
