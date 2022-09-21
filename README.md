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
- mkdir - makes a new directory
- rmdir - removes a directory
- rmdir -r - removes a non-empty directory by removing everything below it
- mv - moves a directory
- chmod - changes file permissions
- echo - writes text specified in quotes, can write it to a file using a carrot - example: 

        echo "this is a text line." > your_filename.txt
        
- cat - prints contents of file
- head - prints first ten lines of file
- tail - prints last ten lines of file 

## Dealing with programs and services

- ps - shows currently running processes
- apt-get install - downloads and installs the specified program. Depending on your version of Linux this might be apt install
- apt-get update - update specified program
