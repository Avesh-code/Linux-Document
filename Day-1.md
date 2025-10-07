# Day 1 of Linux
## Basic Commands 

`cd` : change the directory  
`cd ..` : go back to parent directory.  
`ls –l` : list all the items that are in current directory.  
`whoami` : who is currently log in as  
`users` : it tell the users present in this computer  
`who` : list of user in minimal ways and when did they last log in  
`w` : info regarding user login system  
`df –h` : to check disk usage  
`ls ch*` : list of files whose name is started by ch in current directory.  
`ls –a` : list of the files present in current directory  
`vim filename` : to create a file in current directory and edit content  
`cat filename` : to display content of that file  
`cat –b filename` : to display the content with line numbers  
`cw filename` : count line, word and character.  
`cw filename1 filename2 filename3` : multiple files counting lines, words, and characters.  
`cp filename1 filename2` : copy the file with other name  
`mv filename2 desti_add` : move the file from current directory to new directory.  
`rm filename` : Delete a specific file from current directory.

>symbolic links and hard links?

## Directories and Directory Structure of Linux System  

| Directory | What it stores |
|:----------|:--------------|
| /         | The main or top folder of the Linux system |
| /bin      | Basic programs your computer needs to run (like copy, move, list files) |
| /boot     | Files to start the computer, including the Linux kernel |
| /dev      | Links to your computer’s hardware (like USB, disks, keyboard) |
| /etc      | Settings and configuration files |
| /home     | Personal folders for each user |
| /lib      | Libraries that help programs run |
| /lost+found | Recovered files if something goes wrong |
| /media    | Folder where USB drives, CDs, and cameras show up automatically |
| /mnt      | Place to temporarily open (mount) other drives |
| /opt      | Extra software installed by you |
| /proc     | Information about running programs and the system |
| /root     | The main admin (root user) folder |
| /sbin     | Special tools for system maintenance (used by admin) |
| /srv      | Files that your computer shares with others (like a website) |
| /sys      | Information about your computer’s hardware |
| /tmp      | Temporary storage for files that can be deleted anytime |
| /usr      | Programs, tools, and libraries for all users |
| /var      | Files that keep changing (logs, emails, print jobs) |  
