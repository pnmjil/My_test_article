# Commonly Used Linux Commands

Here's a clean and practical list of Common Linux Commands for Rocky Linux (and most Linux distributions):

## 1. Navigation Commands

| Command  | Description                     |
| -------- | ------------------------------- |
| pwd      | Show current directory          |
| ls       | List files and folders          |
| ls -la   | List all files including hidden |
| cd /path | Change directory                |
| cd ~     | Go to home directory            |
| cd -     | Go back to previous directory   |

## 2. File & Folder Management

| Command               | Description                  |
| --------------------- | ---------------------------- |
| mkdir <folder_name >  | Create a new folder          |
| touch <filename.txt>  | Create an empty file         |
| cp file1 file2        | Copy file                    |
| cp -r folder1 folder2 | Copy folder recursively      |
| mv oldname newname    | Move or rename file/folder   |
| rm filename           | Delete file                  |
| rm -r foldername      | Delete folder and contents   |
| rm -rf foldername     | Force delete (use carefully) |

## 3. Viewing & Editing Files

| Command       | Description                |
| ------------- | -------------------------- |
| cat filename  | Display file content       |
| less filename | View file page by page     |
| nano filename | Edit file with Nano editor |
| vim filename  | Edit with Vim (advanced)   |
| head filename | Show first 10 lines        |
| tail filename | Show last 10 lines         |
| tail -f file  | Live view (log files)      |

## 4. System Information

| Command  | Description                           |
| -------- | ------------------------------------- |
| whoami   | Current username                      |
| hostname | Show hostname                         |
| uname -a | System information                    |
| df -h    | Disk space usage                      |
| free -h  | Memory (RAM) usage                    |
| top      | Live process monitor                  |
| htop     | Better process monitor (if installed) |

## 5. Package Management (Rocky Linux)

| Command                       | Description         |
| ----------------------------- | ------------------- |
| sudo dnf update               | Update all packages |
| sudo dnf install package-name | Install a package   |
| sudo dnf remove package-name  | Remove a package    |
| sudo dnf search keyword       | Search for packages |

## 6. Permissions & Users

| Command               | Description             |
| --------------------- | ----------------------- |
| ls -l                 | View permissions        |
| chmod 755 filename    | Change file permissions |
| chown user:group file | Change owner            |
| sudo command          | Run command as root     |

## 7. Network Commands

| Command         | Description       |
| --------------- | ----------------- |
| ip addr         | Show IP address   |
| ping google.com | Test connectivity |
| curl google.com | Fetch web page    |
| wget url        | Download file     |

## 8. Search & Find

| Command              | Description                  |
| -------------------- | ---------------------------- |
| grep "text" filename | Search text in file          |
| grep -r "text" /path | Recursive search             |
| find / -name "*.txt" | Find files by name           |
| locate filename      | Fast search (needs updatedb) |

## 9. Archive & Compression

| Command                  | Description               |
| ------------------------ | ------------------------- |
| tar -cvf archive.tar dir | Create tar archive        |
| tar -xvf archive.tar     | Extract tar               |
| tar -czvf archive.tar.gz | Create compressed archive |
| unzip file.zip           | Extract zip file          |

## 10. User & Process Management

| Command       | Description            |
| ------------- | ---------------------- |
| ps aux        | List running processes |
| kill PID      | Kill process by ID     |
| kill -9 PID   | Force kill process     |
| su - username | Switch user            |
| sudo command  | Run as superuser       |

## 11. Git Commands

| Command              | Description       |
| -------------------- | ----------------- |
| git clone url        | Clone repository  |
| git status           | Check status      |
| git add .            | Stage all changes |
| git commit -m "msg"  | Commit changes    |
| git push origin main | Push to GitHub    |
| git pull             |                   |
