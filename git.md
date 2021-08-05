# Git
* Distribution version controll system.
* Keep a track of everything.
* Used for interacting of multiple users. 

# Git Command

| Command   |      Syntax     |  Description |
|----------|-------------|------|
|  git config |    git config --global user.name " Your name"           | If any commit form my side then it will show my name.    |
||git config --global user.email "rai@example.com"|If any commit form my side then it will show my email.|
|git init||Initialize empty git repository in folder.|
| git add| git add "filename"|We put untracked file to the staged area.|
||git add -A|It is used add one file or more no of file|
|git status||Show the current status of git tree.|
|git log||History of all commits.|
|git commit|git commit -m "commit message"|Changes of file to the local repository.|
||git commit -a -m "commit message"|commit all the stages.|
|git diff||Show the modified file before commit.|
||git branch "branch name"| Create a new branch|
|git branch|git checkout "branch name"| Switch to specified branch. |
||git branch "branch name" -D|Delete a branch|
||git checkout -b "branch name"|Create a new branch and directly switch to that branch. |
|git stash||Create a git repository back up files into another location without commit.|
||git stash pop| Files stashed are recover back .|
|git clone|git clone "url"|Recover file form remote server repository.|
|git fetch|git fetch origin "branch name"|Recover branch form remote server repository.|
|git merge|git merge "branch name"|Merge individual branch to specified branch. |
|git pull|git pull origin "branch name"|Pulls the changes of remote repository in the local repository.|
|git push|git push origin "branch name"|Push the changes of local  repository to remote repository.|

# Git Workflow

* Untracked file :- Git is not record any changes at untracked files.If we want git should record are changes then fill put in to staged file.

* Staged file :- In staged file means git is now record the file 
 if any a changes is done.after staged file we should commit the file. 

<p align ="center"/><img src ="images/git work flow.jpg" width ="230%" />

* Unmodified file :- Unmodified file means after commit their is no file.

* Modified file :- modified  file means after commit user has edit in the file then we have to put in staged file and after that we should have to commit.

# Creating a New branch on Master branch

<p align ="center"/><img src ="images/new branch.jpg" width ="230%" />