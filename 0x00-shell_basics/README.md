#!/bin/bash
pwd     prints the absolute path name of the current working directory
ls      displays the contents list of your current directory
cd ~    changes the working directory to the user’s home directory
ls -l   displays current directory contents in a long format
ls -la  displays current directory contents, including hidden files (starting with .)
ls -na  displays current directory contents
mkdir /tmp/my_first_directory           creates a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory   moves the file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_directory/betty        deletes the file betty
rm -r /tmp/my_first_directory/          deletes the directory my_first_directory that is in the /tmp directory
cd -    changes the working directory to the previous one
ls -la . .. /boot      lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
file /tmp/iamafile     prints the type of the file named iamafile. The file iamafile will be in the /tmp directory
ln -s /bin/ls  __ls__  creates a symbolic link to /bin/ls, named __ls__
cp -un *.html ../      copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
mv [[:upper:]]* /tmp/u       creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u
rm *~    deletes all files in the current working directory that end with the character ~
mkdir -p welcome/to/school   creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
ls -amp | sort -d       lists all the files and directories of the current directory, separated by commas
0 string SCHOOL School data      !:mime School   can be used with the command file to detect School data files
