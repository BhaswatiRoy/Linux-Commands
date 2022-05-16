After creating Linux Enviroment in Virtual Machine ~

1. `sudo apt install gcc make perl` - installing important libraries before we begin with working of Linux commands
2. `man` - display inbuilt documentation/manual for any command //using '/' in man page and typing a phrase takes us to the part containing exact phrase
3. `ls` - lists all the items under a particular location
4. `clear` - clear all the commands in the screen
5. `apropos` - search the manual command names & description for a phrase specifically mentioned //using double quotes brings exact match with given phrase
6. `df` - report file system disk space usage details
7. `stat` - display file or file system statistics/status
8. `file` - determine file type of a given file
9. `cd` - change directory
10. `~` - refers to current user's home directory as the shell expands the tilde character to the path of user's home directory
11. `pwd` - display the absolute path of current working directory
12. `..` - signifies the last directory of current directory
13. `mkdir` - creates new directories inside current directory, multiple directories can be created by mentioning with space separation
14. `rmdir` - deletes directories inside current directory
15. `cp` - copies data inside option 1 to option 2 written after the command
16. `find . -name` - finds file with name passed as parameter //using name with "" gives exact file and using * completes the name like "documents" lists 1 directory/file. "d*" lists multiple directory/file whose name starts with 'd'. "*d*" lists multiple directory/file whose name contains 'd'.
17. `/root` - without logging in we will we shown 'permission denied'
18.  `sudo ls /root` - prompted to type root user password to login (3 attempts only) //after a few min of giving password we will no more be asked for password for sometime
19.  `sudo -k` - stops root user's priviledges and after that using root user commands we need to enter password again
20.  `sudo -s` - entirely loggs us into root user account for long time of work after we enter password
21.  `exit` - exit from root user and return back to normal user
22.  `ls -l directoryname` - when this command is run inside the directory which contains the mentioned directory then we get to see the file permissions for each
23.  `chmod` - change permissions of the file by entering permissions(octa/symbolic) & filename as options
24.  `./` - when used before a file name under a directory then it runs that file
25.  `cat` - display the contents of the file when we have read permissions
26.  `touch` - creates new file by file name & attributes given as options
27.  `nano` - change the file 
28.  `ln -s` - creates soft links from b to a file // ln -s a b //softlinks point to files
29.  `ln` - creates hard links from b to a file // ln a b //hardlinks point to exact data
30.  
