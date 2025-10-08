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
`vim filename` : it is editor to create a file in current directory and edit content  
`cat filename` : to display content of that file  
`cat –b filename` : to display the content with line numbers  
`cw filename` : count line, word and character.  
`cw filename1 filename2 filename3` : multiple files counting lines, words, and characters.  
`cp filename1 filename2` : copy the file with other name  
`mv filename2 desti_add` : move the file from current directory to new directory.  
`rm filename` : Delete a specific file from current directory.

> symbolic links and hard links?

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

> `cd` is mainly used for changing directories

`cd ~` : to go to Home directory  
`cd ~Username` : to go to Home of any specific user  
`cd -` : to go to last Directory.  

> Absolute and Relative Path  

`mkdir new1 new2` : it will make a 2 new folders  
`mkdir -p /etc/new2/new1` : it is used for also making parent folder  
`rmdir new1 new2` : It will delete the folders.  
`mv filename1 filename-new` : it used for renaming a file.  
`.(dot)` : it is for current directory.  
`..(dot)(dot)` : it is a uper directory or parent directory of current  

> File Permission and access control

>There are 3 Diffrent Permission Acosiated with
> 1. for the file owner(2 to 4 letters)
> 2. for the group(5 to 7 letters)
> 3. for the others(8 to 10 letters)

>r(read) w(write) x(execute)

>changing permission (chmod) it is used for changing permissions for files

`chmod o+r,u-r,g=rx filename` : it is change permission using symbolic means  
>o=others
>u=user
>g=group

`chmod 755 filename` : it is chnage permission using numbers.  

| Number | Octal Permission Representation | Ref      |
|:-------|:--------------------------------|:---------|
| 0      | No permission                   | ---      |
| 1      | Execute permission              | --x      |
| 2      | Write permission                | -w-      |
| 3      | Execute and write permission    | -wx      |
|        | (1 execute + 2 write = 3)      |          |
| 4      | Read permission                 | r--      |
| 5      | Read and execute permission     | r-x      |
|        | (4 read + 1 execute = 5)       |          |
| 6      | Read and write permission       | rw-      |
|        | (4 read + 2 write = 6)          |          |
| 7      | All permissions                 | rwx      |
|        | (4 read + 2 write + 1 execute = 7) |       |  

>change owner and change group (chown) (chgrp)

`chown user filelist` : so now the owner of that file list is change.  
`chgrp group file` : so now the for file is changed.  
