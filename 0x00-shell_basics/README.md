pwd - writes a script that prints the absolute path name of the current working directory.
ls - Displays the contents list of your current directory.
cd ~ - a script that changes the working directory to the user’s home directory.
ls -l - Displays current directory contents in a long format.
ls -al - Displays  current directory contents, including hidden files (starting with .). Use the long format.
ls -lan - Displays current directory contents in Long format,with user and group IDs displayed numerically and hidden files (starting with .)
mkdir /tmp/my_first_directory - A script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory/ - Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty - deletes betty, which is in /tmp/my_first_directory.
rm -r /tmp/my_first_directory - Deletes the directory my_first_directory that is in the /tmp directory.
cd - - changes the working directory to the previous one.
ls -la . .. /boot -  a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile - prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
ln -s /bin/ls _ls_ - Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
cp -u *.html .. - copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.You can consider that all HTML files have the extension .html
mv [[:upper:]]* /tmp/u - moves all files beginning with an uppercase letter to the directory /tmp/u.
rm *~ - deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school -  creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
ls -xamp -  lists all the files and directories of the current directory, separated by commas (,).