# bash

Here's a sample `.readme` file for your GitHub repo with a list of useful and common Bash commands:

---

# Bash Commands Cheat Sheet

A collection of useful and commonly used **Bash** commands for quick reference. Perfect for developers and system administrators.

## Table of Contents
- [File and Directory Operations](#file-and-directory-operations)
- [Searching and Viewing Files](#searching-and-viewing-files)
- [Permissions](#permissions)
- [Process Management](#process-management)
- [System Information](#system-information)
- [Networking](#networking)
- [Archiving and Compression](#archiving-and-compression)
- [Text Processing](#text-processing)
- [Git Commands](#git-commands)
- [Miscellaneous](#miscellaneous)

---

## File and Directory Operations

- **Change directory**  
  `cd /path/to/directory`  
  Change the current directory to the specified path.

- **List files in a directory**  
  `ls`  
  List files and directories in the current directory.

- **List files with details**  
  `ls -l`  
  Show file permissions, size, owner, and modification date.

- **Create a directory**  
  `mkdir directory_name`  
  Create a new directory.

- **Remove a directory**  
  `rmdir directory_name`  
  Remove an empty directory.

- **Remove a file**  
  `rm file_name`  
  Delete a file.

- **Copy a file**  
  `cp source_file destination`  
  Copy a file from source to destination.

- **Move or rename a file**  
  `mv source_file destination`  
  Move or rename a file.

- **Create an empty file**  
  `touch filename`  
  Create an empty file or update its timestamp.

---

## Searching and Viewing Files

- **Search for a file by name**  
  `find /path/to/search -name "filename"`  
  Find a file by name in a given path.

- **Search for a string inside a file**  
  `grep "search_string" filename`  
  Search for a specific string in a file.

- **Display the first N lines of a file**  
  `head -n N filename`  
  Show the first N lines of a file.

- **Display the last N lines of a file**  
  `tail -n N filename`  
  Show the last N lines of a file.

- **Display live updates to a file**  
  `tail -f filename`  
  Continuously output the end of the file (e.g., for logs).

---

## Permissions

- **Change file permissions**  
  `chmod permissions filename`  
  Modify the permissions of a file or directory.

- **Change file owner**  
  `chown user:group filename`  
  Change the owner and group of a file or directory.

- **View file permissions**  
  `ls -l filename`  
  Show file permissions.

---

## Process Management

- **View running processes**  
  `ps aux`  
  List all running processes.

- **Search for a process**  
  `ps aux | grep process_name`  
  Search for a specific process by name.

- **Kill a process**  
  `kill PID`  
  Terminate a process using its PID (Process ID).

- **Kill a process by name**  
  `pkill process_name`  
  Kill a process by its name.

- **Show system resource usage**  
  `top`  
  Display real-time system resource usage (CPU, memory).

---

## System Information

- **Display system information**  
  `uname -a`  
  Display kernel and system information.

- **Check disk usage**  
  `df -h`  
  Show disk usage of all mounted filesystems in human-readable format.

- **Check memory usage**  
  `free -h`  
  Show memory usage in human-readable format.

- **Show system uptime**  
  `uptime`  
  Display how long the system has been running.

- **Show CPU info**  
  `lscpu`  
  Display CPU architecture information.

---

## Networking

- **Check network interfaces**  
  `ifconfig`  
  Show network interface configuration (requires sudo).

- **Ping a server**  
  `ping server_address`  
  Test network connectivity to a server.

- **Check open ports**  
  `netstat -tuln`  
  List open ports and listening services.

- **Display routing table**  
  `route -n`  
  Show the routing table for the network.

- **Get external IP address**  
  `curl ifconfig.me`  
  Display your public IP address.

---

## Archiving and Compression

- **Create a tarball archive**  
  `tar -cvf archive_name.tar directory_name`  
  Create a tar archive of a directory.

- **Extract a tarball archive**  
  `tar -xvf archive_name.tar`  
  Extract files from a tar archive.

- **Create a compressed tarball**  
  `tar -czvf archive_name.tar.gz directory_name`  
  Create a compressed tar archive (gzip).

- **Extract a compressed tarball**  
  `tar -xzvf archive_name.tar.gz`  
  Extract files from a compressed tar archive (gzip).

- **Create a zip archive**  
  `zip -r archive_name.zip directory_name`  
  Create a zip archive.

- **Extract a zip archive**  
  `unzip archive_name.zip`  
  Extract files from a zip archive.

---

## Text Processing

- **Sort lines in a file**  
  `sort filename`  
  Sort the lines of a file in ascending order.

- **Count the number of lines in a file**  
  `wc -l filename`  
  Count the number of lines in a file.

- **Replace text in a file**  
  `sed -i 's/old_text/new_text/g' filename`  
  Replace all occurrences of `old_text` with `new_text` in a file.

- **Display a column from a file**  
  `cut -d' ' -f1 filename`  
  Show the first column (delimited by space) of a file.

- **Display a file in reverse**  
  `tac filename`  
  Display the contents of a file in reverse order.

---

## Git Commands

- **Clone a repository**  
  `git clone https://github.com/user/repository.git`  
  Clone a Git repository to your local machine.

- **Check repository status**  
  `git status`  
  Show the current status of the working directory.

- **Add changes to staging area**  
  `git add file_name`  
  Add a file to the staging area.

- **Commit changes**  
  `git commit -m "commit message"`  
  Commit staged changes with a message.

- **Push changes to remote repository**  
  `git push origin branch_name`  
  Push local commits to a remote repository.

- **Pull changes from remote repository**  
  `git pull origin branch_name`  
  Fetch and merge changes from a remote repository.

- **View commit history**  
  `git log`  
  View the commit history of the repository.

- **Create a new branch**  
  `git branch branch_name`  
  Create a new Git branch.

- **Switch to a branch**  
  `git checkout branch_name`  
  Switch to the specified branch.

---

## Miscellaneous

- **Check the manual for a command**  
  `man command_name`  
  Open the manual for a specific command.

- **Clear the terminal screen**  
  `clear`  
  Clear the terminal screen.

- **Exit the terminal**  
  `exit`  
  Close the terminal session.

---

Feel free to contribute or make suggestions for additional commands!

---

This `.readme` file contains essential Bash commands for common tasks, organized for easy access. You can always customize it with more specific commands or examples as per your project needs!
