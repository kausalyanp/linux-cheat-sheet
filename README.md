# linux-cheat-sheet
This Cheat Sheet coontains most commnly and very uncommonly used linux commands.

## Table of Contents:
1. File and Directory Management
2. File Content Manipulation
3. File Permissions
4. System Monitoring
5. Network Commands
6. Process Management
7. Archiving and Compression
8. User Management
9. Package Management (Debian/Ubuntu)
10. Others

## 1. File and Directory Management
* ls: Lists files and directories.
  - Example: ls -l (detailed list view)
* cd: Changes the current directory.
  - Example: cd /home/user
* pwd: Displays the current working directory.
  - Example: pwd
* mkdir: Creates a new directory.
  - Example: mkdir new_folder
* rmdir: Removes empty directories.
  - Example: rmdir old_folder
* rm: Deletes files or directories.
  - Example: rm file.txt, rm -r folder (recursive delete)
* cp: Copies files or directories.
  - Example: cp file1.txt file2.txt
* mv: Moves or renames files or directories.
  - Example: mv file1.txt new_file.txt
* touch: Creates a new empty file.
  - Example: touch newfile.txt
* find: Searches for files and directories.
  - Example: find / -name file.txt
* locate: Finds files and directories quickly using a database.
  - Example: locate file.txt

## 2. File Content Manipulation
* cat: Displays the content of a file.
    - Example: cat file.txt
* tac: Displays the content of a file in reverse.
    - Example: tac file.txt
* less: Opens a file for viewing (scrollable).
    - Example: less file.txt
*  more: Views file content (less advanced than less).
    - Example: more file.txt
* head: Displays the first few lines of a file.
    - Example: head -n 10 file.txt
* tail: Displays the last few lines of a file.
    - Example: tail -n 10 file.txt
* nano: Opens a file in a simple text editor.
    - Example: nano file.txt
* vim: Opens a file in the Vim text editor.
    - Example: vim file.txt
* wc: Counts words, lines, and characters in a file.
    - Example: wc file.txt

## 3. File Permissions
* chmod: Changes file or directory permissions.
    - Example: chmod 755 file.txt
* chown: Changes file ownership.
    - Example: chown user:group file.txt
* chgrp: Changes group ownership of a file.
    - Example: chgrp group file.txt
* umask: Sets default permissions for new files and directories.
    - Example: umask 022
## 4. System Monitoring
* top: Displays real-time processes and resource usage.

* htop: An interactive version of top (needs to be installed).

*  ps: Lists running processes.
    - Example: ps aux
* df: Shows disk space usage.
    - Example: df -h
* du: Displays disk usage of a directory or file.
    - Example: du -h folder
* free: Displays memory usage.
    - Example: free -h
* uptime: Shows system uptime.
    - Example: uptime
* who: Displays logged-in users.
    - Example: who
* w: Shows who is logged in and what they are doing.
    - Example: w
 
## 5. Network Commands
















