# Git Interview Questions & Answers (DevOps - 3-5 Years)

---

## 1. What is Git?
Git is a distributed version control system used to track changes in code.  
It allows multiple developers to work on the same project without overwriting each other's work.  
Each developer has a local copy of the repository, which improves speed and reliability.

---

## 2. Difference between Git and GitHub?
Git is a command-line tool used for version control.  
GitHub is a cloud platform where Git repositories are stored and shared.  
GitHub also provides features like pull requests, code review, and collaboration.

---

## 3. What is a repository?
A repository (repo) is a storage location for your project.  
It contains your code, configuration files, and the complete history of changes.  
Repos can be local (on your system) or remote (on platforms like GitHub).

---

## 4. What is a commit?
A commit is a snapshot of your code at a particular point in time.  
Each commit has a unique ID and a message describing the changes.  
Commits help track what changes were made and by whom.

---

## 5. What is a branch?
A branch is a separate line of development.  
It allows you to work on new features or bug fixes without affecting the main code.  
Once work is complete, it can be merged back into the main branch.

---

## 6. What is the main branch?
The main (or master) branch is the default branch in a repository.  
It usually contains stable and production-ready code.  
Teams often protect this branch using rules like code reviews.

---

## 7. What is git clone?
`git clone` is used to copy a remote repository to your local machine.  
It downloads all files, branches, and commit history.  

Example:
git clone <repo-url>

---

## 8. What is git pull?
`git pull` is used to get the latest changes from a remote repository and merge them into your current branch.  
It is a combination of `git fetch` + `git merge`.

---

## 9. What is git push?
`git push` uploads your local commits to the remote repository.  
It is commonly used after committing your changes to share them with the team.

---

## 10. What is git fetch?
`git fetch` downloads the latest changes from the remote repository but does not merge them.  
This allows you to review changes before applying them.

---

## 11. Difference between pull and fetch?
- `git fetch` → downloads changes only  
- `git pull` → downloads and merges changes automatically  
Fetch is safer when you want control over merging.

---

## 12. What is git status?
`git status` shows the current state of your working directory.  
It tells which files are modified, staged, or untracked.

---

## 13. What is staging area?
The staging area is an intermediate space where you prepare changes before committing.  
It allows you to select specific changes instead of committing everything at once.

---

## 14. What is git add?
`git add` moves files to the staging area.  
You can add a single file or all files before committing.

Example:
git add file.txt
git add .

---

## 15. What is git merge?
`git merge` is used to combine changes from one branch into another.  
It keeps the history of both branches and creates a merge commit.

---

## 16. What is merge conflict?
A merge conflict happens when two branches modify the same part of a file.  
Git cannot decide which change to keep, so manual resolution is required.  
After resolving, you must commit the changes.

---

## 17. What is git rebase?
`git rebase` moves your branch to the latest commit of another branch.  
It rewrites commit history to make it linear and cleaner.  
It is commonly used before merging feature branches.

---

## 18. Difference between merge and rebase?
- Merge keeps full history and creates a merge commit  
- Rebase rewrites history and creates a clean linear flow  

Merge is safer, rebase is cleaner.

---

## 19. What is git stash?
`git stash` temporarily saves your uncommitted changes.  
This is useful when you want to switch branches without committing incomplete work.  
Later, you can apply the changes back.

---

## 20. What is git log?
`git log` shows the history of commits in a repository.  
It includes commit ID, author, date, and message.  
Useful for debugging and tracking changes.

---

## Bonus: How Git is used in DevOps?
In DevOps, Git plays a key role in CI/CD pipelines:
- Code push triggers Jenkins/GitHub Actions pipelines  
- Helps manage infrastructure as code (Terraform, Ansible)  
- Enables version control for deployments  
- Supports branching strategies for releases  

Example:
Developer pushes code → Pipeline triggers → Build → Test → Deploy

---
