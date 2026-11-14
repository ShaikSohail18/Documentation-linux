Day 1 - Linux Commands

1. Navigation & Basics
- pwd - where am I now
- ls - list files
- ls -la - list all + hidden + permissions
- ls -lh - list with human readable size
- cd folder - go into folder
- cd .. - go back one folder
- cd ~ - go to home
- clear - clear screen
- whoami - which user am I
- history - show commands I typed before

2. File & Folder Operations
- touch file.txt - create empty file
- mkdir myfolder - create folder
- mkdir -p a/b/c - create nested folders
- cp file1 file2 - copy file
- cp -r folder1 folder2 - copy folder
- mv old new - move / rename
- rm file.txt - delete file
- rm -rf folder - delete folder forcefully
- cat file.txt - show file content
- head -n 10 file.txt - first 10 lines
- tail -n 10 file.txt - last 10 lines
- nano file.txt - edit file in terminal

3. Search & Find
- find / -name "*.log" - find file by name
- grep "error" file.txt - search word in file
- grep -r "error" /var/log/ - search in all files
- grep -i "Error" file.txt - search ignore case
- which python3 - where is program installed

4. Permissions
- ls -l - see permissions
- chmod +x script.sh - make file executable
- chmod 755 file - give rwx to owner, rx to others

5. Users & Groups
- id - my user id and groups
- adduser sohail - create new user
- who - who is logged in

6. Networking - Cloud Engineer Core
- ping google.com - check internet
- ip a - show my IP address
- hostname -I - show my private IP
- curl google.com - test website from terminal
- wget https://example.com/file.zip - download file
- ss -tulpn - which ports are open
- ssh user@server-ip - login to remote server
- scp file.txt user@server:/tmp/ - copy file to server
