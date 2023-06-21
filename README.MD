# learn-git

Git is a source control system. 

The foundation feature of GIT is version control system. 

It is open source and light weight.

Git operates a distributed source control system.

## Useful git commands

--- config settings

git config --global user.name "myusername"

git config --global user.email "example@example.com"

git config --global credential.github.com.useHttpPath true


--- initialize repo, add file and initial commit to local

git init    -- initialize git repository

git branch -M main

git add --all or specific file name

git add <filename>

git commit -m "initial commit"

--- push changes to remote

git remote add origin <http://github.com/myrep.git>

git push origin -u main


---- list, checkout branch, pull changes from remote 
git branch (to list the branch locally)

git checkout master

git pull origin master

git checkout -b dev

git status

git commit -am "initial commit"

git push -u origin dev

git branch --r --list

git branch -d branch_name (local branch to delete)

git push main --delete branch_name ( delete remote branch)

---- filter list of branches that has name eg. ops-*

git branch | grep "ops-*"

--- filter and delete
git branch | grep "ops-*" | xargs git branch -D


--- to store, apply, list, show and clear changes locally

git stash

git stash apply --index 0

git stash list

git stash show

git stash clear

