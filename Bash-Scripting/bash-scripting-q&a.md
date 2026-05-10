# Bash Scripting Interview Questions & Answers (DevOps - 3-5 Years)

---

## 1. What is a Bash script?
A Bash script is a file containing a series of commands that are executed in sequence.  
It is used to automate repetitive tasks like deployments, backups, and monitoring.

---

## 2. What is a shebang (#!)?
Shebang defines which interpreter should execute the script.

Example:
#!/bin/bash

It tells the system to use bash to run the script.

---

## 3. How do you run a Bash script?
Make it executable:
chmod +x script.sh

Run it:
./script.sh

---

## 4. What are variables in Bash?
Variables store values that can be reused in a script.

Example:
name="Aravind"
echo $name

---

## 5. Difference between $var and ${var}?
Both are used to access variable values.  
`${var}` is safer when combining with other text.

Example:
echo "${name}_devops"

---

## 6. What is user input in Bash?
You can take input using `read`.

Example:
read name
echo "Hello $name"

---

## 7. What is an if condition?
Used to make decisions in scripts.

Example:
if [ $a -gt 10 ]; then
  echo "Greater"
fi

---

## 8. What are loops in Bash?
Loops repeat tasks.

Types:
- for loop
- while loop

Example:
for i in 1 2 3
do
  echo $i
done

---

## 9. What is exit status?
Every command returns a status:
- 0 → success  
- non-zero → failure  

Used for checking success of commands.

---

## 10. What is $??
`$?` stores the exit status of the last command.

Example:
ls
echo $?

---

## 11. What is $0, $1, $2?
These are positional parameters:
- $0 → script name  
- $1, $2 → arguments passed to script  

Example:
./script.sh file.txt

---

## 12. What is a function in Bash?
A function is a reusable block of code.

Example:
hello() {
  echo "Hello"
}
hello

---

## 13. What is set -e?
`set -e` stops the script if any command fails.  
Useful in automation to avoid partial execution.

---

## 14. What is set -x?
`set -x` prints commands before executing them.  
Used for debugging scripts.

---

## 15. What is redirection?
Used to redirect output.

Examples:
echo "Hi" > file.txt   (overwrite)
echo "Hi" >> file.txt  (append)

---

## 16. What is a pipe (|)?
Pipe sends output of one command to another.

Example:
ps -ef | grep java

---

## 17. How to check file exists?
Example:
if [ -f file.txt ]; then
  echo "File exists"
fi

---

## 18. What is cron job?
Used to schedule scripts at specific times.

Example:
crontab -e

Runs script every day automatically.

---

## 19. What is difference between == and -eq?
- `==` → string comparison  
- `-eq` → numeric comparison  

---

## 20. How Bash is used in DevOps?
Bash scripting is used for:
- Automation (deployments, backups)
- Monitoring scripts
- CI/CD pipeline steps
- Server setup and configuration

---

## Bonus Example (Real Use Case)

Backup script:
tar -czf backup.tar.gz /data

Used in production to automate backups.

---
