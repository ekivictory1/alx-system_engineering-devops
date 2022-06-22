**This is a command to print the path of the working directory**

# Description of function of bash scripts in this directory

This directory contains bash scripts that perform various common
command line tasks. 

## 0-current_working_directory

Prints the absolute path name of the current working directory.

## 1-listit

Displays the contents list of your current directory.

## 2-bring_me_home

Changes the working directory to the user's home directory.

## 3-listfiles

Displays current directory's content list in long format.

## 4-listmorefiles

Displays current directory's content list, including hidden files (starting with .).
in long format.

## 5-listfilesdigitonly

Displays current directory's contents as follows:

1. In long format
2. With user and group IDs displayed numerically
3. Including hidden files

## 6-firstdirectory

Creates a directory named my_first_directory in the /tmp/ directory.

## 7-movethatfile

Move the file betty from /tmp/ to /tmp/my_first_directory.

## 8-firstdelete

Delete the file named betty

## 9-firstdirdelte

Delete the directory my_first_directory that is in the /tmp directory.

## 10-back

Changes the working directory to the previous one.

## 11-lists

Displays a list of the files (including files beginning with a period, which are
usually hidden) in the following directories in the given order:

1. current directory
2. parent directory
3. /boot directory

## 12-file_type

Prints the type of a file named iamafile in the /tmp directory.

## 13-symbolic-link

Creates a symbolic link to /bin/ls named __ls__ in the 
current working directory.

## 14-copy_html

Copies all html files from the current working directory to its
parent directory, but only copies files that did not exist or were newer
than the versions in the parent directory of the working directory.

It is assumed that all html files end with a .html extension.

## 15-lets_move

Moves all the files strting with an uppercase letter to the 
/tmp/u directory. It is assumed the /tmp/u directory already exists.

## 16-clean_emacs

Deletes all files in the current working directory that end with the 
tilde(~) character.

## 17-tree

Creates the directories:
	- welcome
	- welcome/to
	- welcome/to/school
using one command.

## 18-commas

Display a list of the current directories files and directories, including
files that begin with a period character in the following format:

1. The list should be comma-separated.
2. The list should be alpha ordered, except for the . and ..
directories which should be listed first.
3. Sort only using digits and letters in that order of precedence.
4. The list should end with a new line.

Assume that each file will have at least one digit or one letter.

## 19-school.mgc

A magic file to be used with 'file' command to detect School files.
School files contain the string 'SCHOOL' at offset 0.