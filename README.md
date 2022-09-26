# linux-commands
Cheat sheet for common Linux commands

## User commands

su - switch user

sudo - run command as root user

## File system and navigation

- ls - lists contents of directory
- ls -a - lists everything, including hidden files or folders
- ls -lh - formats the list in an easier-to-read format
- cd - change directory
- cd .. - move up one directory
- pwd - print working directory
- mkdir - makes a new directory, -p allows you to create parent and child directory 

        mkdir -p asia/china

- rmdir - removes a directory
- rmdir -r - removes a non-empty directory by removing everything below it
- mv - moves a directory, first arg is original location, second arg is new location

        mv asia/china countries/china

- chmod - changes file permissions
- touch - creates a new file
- echo - writes text specified in quotes, can write it to a file using a carrot - example: 

        echo "this is a text line." > your_filename.txt
        
- cat - prints contents of file
- head - prints first ten lines of file
- tail - prints last ten lines of file 

## Dealing with programs and services

- ps - shows currently running processes
- apt-get install - downloads and installs the specified program. Depending on your version of Linux this might be apt install
- apt-get update - update specified program
- /opt - directory for installing external applications that aren't part of this Linux distro

## Shell changes

- echo $SHELL - displays current shell
- chsh - changes the shell to whatever you specify

## Host machine

- uname -r - checks kernel version
- dmesg - displays kernel messages
- lsblk - view blocks on disk
- init <OPTIONS> <COMMAND> - sends control commands to the init daemon - run init --help to see run levels (see below)
  
        Commands:
        0              Power-off the machine
        6              Reboot the machine
        2, 3, 4, 5     Start runlevelX.target unit
        1, s, S        Enter rescue mode
        q, Q           Reload init daemon configuration
        u, U           Reexecute init daemon

