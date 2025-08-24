# Linux Commands Cheat Sheet

This document contains basic and advanced Linux commands with short descriptions.

---

## 🖥️ System Monitoring

* `top` → Show running processes and CPU usage.
* `df -h` → Display disk usage in human-readable format.
* `free` → Show RAM usage.
* `free -h` → RAM usage in human-readable format.
* `vmstat` → Display system performance (CPU, memory, I/O).
* `vmstat -a` → Show memory activity with active/inactive memory.

---

## 📂 File & Directory Management (Basic)

* `pwd` → Print working directory.
* `ls` → List files.
* `ls -l` → List with details (permissions, owner, size, date).
* `ls -ltr` → List in reverse time order (oldest first).
* `ls -la` → List all files (including hidden).
* `cd` → Change directory.
* `mkdir <Folder_Name>` → Create new folder.
* `touch <File_Name>` → Create an empty file.
* `rm <File_Name>` → Remove a file.
* `rm -r <Folder_Name>` → Remove folder and its contents.
* `rmdir <Folder_Name>` → Remove an empty folder.
* `cat <File_Name>` → Show file content.
* `zcat <File_Name>` → Show content of a compressed file.
* `echo "Message"` → Print a message to terminal.
* `echo "Message" > <File_Name>` → Write message into file (overwrite).
* `head <File_Name>` → Show first 10 lines of a file.
* `head -n 5 <File_Name>` → Show first 5 lines of a file.
* `tail <File_Name>` → Show last 10 lines of a file.
* `tail -n 5 <File_Name>` → Show last 5 lines of a file.
* `tail -f <File_Name>` → Continuously watch file (useful for logs).
* `less <File_Name>` → View file content with navigation.
* `more <File_Name>` → View file content page by page.
* `clear` → Clear the terminal screen.

---

## 📦 File & Folder Operations (Advanced)

* `cp <src File/Folder> <dest Folder>/` → Copy file/folder.
* `cp -r <src Folder>/ <dest Folder>/` → Copy folder recursively.
* `mv <src File/Folder> <dest Folder>/` → Move file/folder.
* `mv <src File/Folder> ../<dest Folder>/` → Move to parent folder.
* `mv <src File> <new FileName>` → Rename a file.
* `wc <File_Name>` → Count words, lines, and characters in file.
* `diff <Src_File> <Dest_File>` → Compare two files.
* `sort <File_Name>` → Sort contents of a file.
* `cut -b 1 <File_Name>` → Cut first character (byte-wise).
* `echo "Message" | tee <File_Name>` → Write message to file and display it.

---

## 🔗 Links

* **Soft Link (Shortcut):**
  `ln -s <path>/<file> <newFileName>`

* **Hard Link:**
  `ln <path>/<file> <newFileName>`

---

## 🔑 Login & Remote Access

* `ssh user_name@Public_Ip_Address` → Connect to remote server via SSH.

---

## 💾 Disk Usage

* `df` → Show disk usage.
* `df -h` → Human-readable disk usage.
* `du .` → Show disk usage of current directory.

---

## ⚙️ Process Management

* `ps` → List processes for current user.
* `top` → Show active processes.
* `fuser .` → Show processes using current directory.
* `kill <PID>` → Kill a process using its Process ID.
* `nohup <command>` → Run command in background even after logout.

---
