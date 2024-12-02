# linux-cheat-sheet
This Cheat Sheet coontains most commnly and very uncommonly used linux commands.

<a name="top"></a>

## Table of Contents:
1. [File and Directory Management](#1-file-and-directory-management)
2. [File Content Manipulation](#2-file-content-manipulation)
3. [File Permissions](#3-file-permissions)
4. [System Monitoring](#4-system-monitoring)
5. [Network Commands](#5-network-commands)
6. [Process Management](#6-process-management)
7. [Archiving and Compression](#7-archiving-and-compression)
8. [User Management](#8-user-management)
9. [Package Management (Debian/Ubuntu)](#9-package-management-debianubuntu)
10. [Others](#10-others)

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

[Back to Top](#top)

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

[Back to Top](#top)

## 3. File Permissions
* chmod: Changes file or directory permissions.
    - Example: chmod 755 file.txt
      
* chown: Changes file ownership.
    - Example: chown user:group file.txt
      
* chgrp: Changes group ownership of a file.
    - Example: chgrp group file.txt
* umask: Sets default permissions for new files and directories.
    - Example: umask 022

[Back to Top](#top)

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

[Back to Top](#top)

## 5. Network Commands
* ping: Tests network connectivity to a host.
    - Example: ping google.com
      
* ifconfig: Displays or configures network interfaces.
    - Example: ifconfig eth0
  
* ip: Configures network interfaces and routing (modern replacement for ifconfig).
    - Example: ip addr
* netstat: Displays network connections and statistics.
    - Example: netstat -tuln
* ss: Displays detailed network statistics (faster than netstat).
    - Example: ss -tuln
* wget: Downloads files from the internet.
    - Example: wget http://example.com/file.txt
* curl: Transfers data from a URL.
    - Example: curl http://example.com

[Back to Top](#top)

## 6. Process Management
* kill: Terminates a process using its PID.
    - Example: kill 1234
      
* killall: Terminates all processes with a specific name.
    - Example: killall firefox
* jobs: Lists background jobs.
    - Example: jobs
* fg: Brings a background job to the foreground.
    - Example: fg %1
* bg: Resumes a background job.
    - Example: bg %1

[Back to Top](#top)

## 7. Archiving and Compression
* tar: Archives files into a tarball.
    - Example: tar -cvf archive.tar files/
      
* gzip: Compresses files using the gzip algorithm.
    - Example: gzip file.txt
* gunzip: Decompresses gzip files.
    - Example: gunzip file.txt.gz
* zip: Compresses files into a zip archive.
    - Example: zip archive.zip file.txt
* unzip: Extracts files from a zip archive.
    - Example: unzip archive.zip

[Back to Top](#top)

## 8. User Management
* whoami: Displays the current logged-in user.
    - Example: whoami
      
* id: Displays user ID, group ID, and other information.
    - Example: id
* adduser: Adds a new user.
    - Example: sudo adduser username
* passwd: Changes the password for a user.
    - Example: passwd
* usermod: Modifies a user account.
    - Example: usermod -aG groupname username
* deluser: Deletes a user account.
    - Example: sudo deluser username

[Back to Top](#top)
 
## 9. Package Management (Debian/Ubuntu)
* apt-get: Installs, upgrades, or removes packages.
    - Example: sudo apt-get install package-name
      
* apt: A user-friendly alternative to apt-get.
    - Example: sudo apt install package-name
* dpkg: Installs or removes .deb packages.
    - Example: sudo dpkg -i package.deb

[Back to Top](#top)
 
## 10. Others
* echo: Displays text.
    - Example: echo "Hello, World!"
      
* date: Shows or sets the system date and time.
    - Example: date
* cal: Displays a calendar.
    - Example: cal
* shutdown: Shuts down the system.
    - Example: sudo shutdown now
* reboot: Reboots the system.
    - Example: sudo reboot
* alias: Creates a shortcut for a command.
    - Example: alias ll='ls -l'
* clear: Clears the terminal screen.
    - Example: clear

[Back to Top](#top)

This repo is created by Kausalya N P
>> Users can copy this for educational purpose.








