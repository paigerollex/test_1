## 1. Create a new repository

* Create new repository in github directory: test_rep

* Create a folder in computer to "host" the remote directory: project_1

* Initialize main folder in computer by copy and pasting github instructions

## 2. Edit files in local -> Github

* To open up file: **start <file name>**

* Check if file is updated: **git status**

* **git add <file name>**

* **git commit -m "commit message"**

* **git push**

## 3. Branches
  
  Purpose: Create a new branch with the same files as main -> make changes in the new branches -> update the main branch with these changes

* Create a new branch & switch to it: **git checkout -b new_branch_name**

* View all branches: **git branch -a**

* Repeat step 2 (except for git push): **git push --set-upstream origin new_branch_name**

* Commit any changes to files in new branch

* Go back to main branch: **git checkout main**

* Merge main branch <- new branch: **git merge new_branch_name**

* Repeat step 2 (except for git add): **git add .**

* Delete the new branch: **git branch -d new_branch_name**

## 4. Edit files in Github -> local

* Note: Merge conflicts occurs when changes are made in Github and in the local

* After making changes in local, repeat step 2

* Resolve any merge conflicts: **git pull**

* Repeat step 2




