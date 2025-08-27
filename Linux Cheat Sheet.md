#  Linux Command Cheat Sheet
by **Igitego , samantha , ndoli **

A quick reference guide for essential Linux commands.  
This cheat sheet is designed for beginners and advanced users who want a fast lookup for common tasks.

---

##  1. File & Directory Management 
Basic commands to navigate and manage files and folders.

| Command | Description |
|---------|-------------|
| `pwd` | Print working directory (current location). |
| `ls` | List files and directories. |
| `ls -l` | List with details (permissions, size, date). |
| `ls -a` | Show hidden files. |
| `cd <dir>` | Change to directory `<dir>`. |
| `cd ..` | Move one directory up. |
| `mkdir <dir>` | Create a new directory. |
| `rmdir <dir>` | Remove an empty directory. |
| `rm -r <dir>` | Remove a directory with its contents. |
| `touch <file>` | Create an empty file. |
| `cp file1 file2` | Copy a file. |
| `mv file1 file2` | Move or rename a file. |

---

##  2. File Viewing & Editing
Commands to read and modify files.

| Command | Description |
|---------|-------------|
| `cat <file>` | Show file contents. |
| `less <file>` | View file page by page. |
| `head <file>` | Show first 10 lines. |
| `tail <file>` | Show last 10 lines. |
| `nano <file>` | Open file in Nano editor. |
| `vim <file>` | Open file in Vim editor. |

---

## 3. Searching & Finding
Search for files and text inside files.

| Command | Description |
|---------|-------------|
| `find <dir> -name "*.txt"` | Find `.txt` files inside `<dir>`. |
| `grep "text" <file>` | Search for `"text"` inside `<file>`. |
| `grep -r "text" <dir>` | Search recursively inside `<dir>`. |
| `which <command>` | Locate a command. |
| `locate <file>` | Quickly find a file using system database. |

---

##  4. File Permissions
Manage who can read, write, or execute files.

| Command | Description |
|---------|-------------|
| `ls -l` | Show permissions for files. |
| `chmod 755 <file>` | Change file permissions. |
| `chown user:group <file>` | Change file ownership. |
| `whoami` | Show current user. |
| `groups` | Show groups you belong to. |

---

##  5. Process Management
View and control running processes.

| Command | Description |
|---------|-------------|
| `ps` | List active processes. |
| `ps aux` | Detailed process list. |
| `top` | Real-time system process viewer. |
| `htop` | Interactive process monitor (better than `top`). |
| `kill <pid>` | Kill process with process ID. |
| `kill -9 <pid>` | Force kill process. |
| `jobs` | Show background jobs. |
| `fg %1` | Bring job 1 to foreground. |

---

##  6. Networking
Commands for connectivity and network management.

| Command | Description |
|---------|-------------|
| `ping <host>` | Check network connectivity. |
| `curl <url>` | Fetch data from a URL. |
| `wget <url>` | Download from the web. |
| `ifconfig` / `ip a` | Show network interfaces. |
| `netstat -tulnp` | Show open ports and listening services. |
| `ssh user@host` | Connect to remote server via SSH. |

---

##  7. Package Management (Ubuntu/Debian)
Install, update, and remove software.

| Command | Description |
|---------|-------------|
| `sudo apt update` | Update package list. |
| `sudo apt upgrade` | Upgrade all packages. |
| `sudo apt install <pkg>` | Install package `<pkg>`. |
| `sudo apt remove <pkg>` | Remove package `<pkg>`. |
| `dpkg -i <pkg.deb>` | Install local `.deb` package. |

---

##  8. Compression & Archiving
Compress and extract files.

| Command | Description |
|---------|-------------|
| `tar -cvf archive.tar dir/` | Create tar archive from directory. |
| `tar -xvf archive.tar` | Extract tar archive. |
| `gzip <file>` | Compress file to `.gz`. |
| `gunzip <file.gz>` | Decompress `.gz` file. |
| `zip file.zip file1 file2` | Create zip file. |
| `unzip file.zip` | Extract zip archive. |

---

##  9. User Management
Manage users and permissions.

| Command | Description |
|---------|-------------|
| `who` | Show logged-in users. |
| `w` | Show users and their activity. |
| `adduser <name>` | Create a new user. |
| `passwd <user>` | Change password for user. |
| `su <user>` | Switch to another user. |
| `sudo <command>` | Run command as root. |

---

##  10. Disk & System Info
Check system health and storage.

| Command | Description |
|---------|-------------|
| `df -h` | Show disk usage (human readable). |
| `du -sh <dir>` | Show size of a directory. |
| `free -h` | Show memory usage. |
| `uname -a` | Show system details. |
| `uptime` | Show system uptime. |
| `dmesg | less` | Show system boot messages. |

---

##  11. Shortcuts & Tricks
Handy shortcuts to speed up work in terminal.

| Shortcut | Description |
|----------|-------------|
| `Ctrl + C` | Stop running command. |
| `Ctrl + Z` | Suspend running process. |
| `!!` | Run last command again. |
| `!ls` | Run last `ls` command. |
| `history` | Show command history. |
| `clear` | Clear the terminal screen. |

---

---

**Tip:** Practice these commands daily to master Linux efficiently.
