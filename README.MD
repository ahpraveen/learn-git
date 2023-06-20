# learn-git

Git is a source control system. 

The foundation feature of GIT is version control system. 

It is open source and light weight.

Git operates a distributed source control system.

## Useful git commands

git init 

git add <filename>

git commit -m "initial commit"

git remote add <http://github.com/myrep.git>

git push origin -u master

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

git branch | grep "ops-*"

git branch | grep "ops-*" | xargs git branch -D

git config --global user.name "myusername"

git config --global user.email "example@example.com"

git config --global credential.github.com.useHttpPath true
