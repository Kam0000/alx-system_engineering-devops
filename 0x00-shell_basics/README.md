pwd command is used to print the current working directory.

ls command is used to display the contents list of the current working directory.

cd displays current directory contents in a long format.

ls -l displays current directory contents in a long format.

ls -a -l displays current directory contents, including hidden files (starting with .).

ls -a -l -n displays current directory contents in long format, with user and group IDs displayed numerically and hidden files.

mkdir /tmp/my_first_directory/ script creates a script that creates a directory named my_first_directory in the /tmp/ directory.

mv /tmp/betty /tmp/my_first _directory script moves the file betty from /tmp/ to /tmp/my_first_directory.

rm /tmp/my_first_directory/betty script deletes the file betty.

rm -r /tmp/my_first_directory script deletes the directory my_first_directory that is in the /tmp directory.

ls -a -l . .. /boot script writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file /tmp/iamafile script writes a script that prints the type of the file named iamafile.

ln -s /bin/ls __ls__ script creates a symbolic link to /bin/ls, named ls.

cp -u *.html .. script creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

mv [[:upper:]]* /tmp/u script creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

rm *~ script creates a script that deletes all files in the current working directory that end with the character ~.

mkdir -p welcome/to/school script creates a script that creates the directories welcome/, welcome/to/ and welcome/to/holberton in the current directory.

ls -pamv script writes a command that lists all the files and directories of the current directory, separated by commas (,).

The last task #19 is used to create a magic filethat can be used with the command 'file' to detect data files.