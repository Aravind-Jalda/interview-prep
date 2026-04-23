# Linux Interview Questions & Answers (DevOps - 4 Years)

---

## 1. What is Linux?
Linux is an open-source operating system used widely in servers and cloud environments.  
It is stable, secure, and highly customizable, which makes it ideal for DevOps work.

---

## 2. What is a shell?
A shell is a command-line interface that allows users to interact with the OS.  
Common shells: bash, sh, zsh.  
In DevOps, we mostly use bash scripting for automation.

---

## 3. What is the difference between root and normal user?
- Root user → has full permissions (admin access)  
- Normal user → limited permissions  

We use `sudo` to execute admin-level commands safely.

---

## 4. What is the pwd command?
`pwd` (print working directory) shows the current directory path.

Example:
pwd

---

## 5. What is the ls command?
`ls` lists files and directories.

Common options:
- `ls -l` → detailed view  
- `ls -a` → shows hidden files  

---

## 6. What is the cd command?
`cd` is used to change directories.

Examples:
cd /home
cd ..
cd ~

---

## 7. What is the cp command?
`cp` is used to copy files or directories.

Example:
cp file1.txt file2.txt

For directories:
cp -r folder1 folder2

---

## 8. What is the mv command?
`mv` is used to move or rename files.

Examples:
mv file1.txt /tmp/
mv old.txt new.txt

---

## 9. What is the rm command?
`rm` deletes files or directories.

Examples:
rm file.txt
rm -r folder/

Be careful, as deletion is permanent.

---

## 10. What is the touch command?
`touch` creates an empty file or updates file timestamp.

Example:
touch file.txt

---

## 11. What is the cat command?
`cat` is used to view file content.

Example:
cat file.txt

---

## 12. What is the grep command?
`grep` is used to search text inside files.

Example:
grep "error" file.log

Used heavily for log analysis in DevOps.

---

## 13. What is the top command?
`top` shows real-time system usage (CPU, memory, processes).

Useful for monitoring system performance.

---

## 14. What is the df command?
`df` shows disk space usage.

Example:
df -h

---

## 15. What is the du command?
`du` shows disk usage of files and directories.

Example:
du -sh folder/

---

## 16. What is chmod?
`chmod` is used to change file permissions.

Example:
chmod 755 script.sh

---

## 17. What is chown?
`chown` changes file ownership.

Example:
chown user:group file.txt

---

## 18. What is ps command?
`ps` shows running processes.

Example:
ps -ef

---

## 19. What is kill command?
`kill` is used to stop a process using its PID.

Example:
kill -9 1234

---

## 20. What is a pipe (|)?
Pipe (`|`) is used to pass output of one command as input to another.

Example:
cat file.txt | grep error

---

## Bonus: How Linux is used in DevOps?
Linux is the base for:
- Servers (EC2, VMs)
- Containers (Docker)
- CI/CD tools (Jenkins)
- Automation scripts

Most DevOps tasks involve writing shell scripts and managing Linux systems.

---
