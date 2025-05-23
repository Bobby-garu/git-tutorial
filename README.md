# git-tutorial
Learn Git here
# Basic GIT Commands used in Corporate life

git init --> for initializing

git status  --> For checking status

git log --> View changes

git clone <repo-link>  -->For cloning a repository

git add <file-name> 
git add .  (or) git add -a  -->adds/stage all the files

git restore <file-name> --> This removes stages changes and back to staging area

git commit -m "Message"  --> Way to commit

Lets say I have not pushed the changes and I want to change the commit message
git commit --amend  --> To edit git message

Go through this for commit message changes befor or after pushing the changes
https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/changing-a-commit-message

git push origin <branch-name>  -->Push a branch to your remote repository

git branch  --> gives you all the branches you have used till date

git branch <branch-name>  --> Create a branch
git branch -d <branch-name>  --> Delete a branch

git branch origin --delete <branch-name>  -->Delete a remote branch  

git checkout <branch-name>  -->Switch to a branch

Create a branch from other branch
git checkout -b <new-branch-name>   --> This will create a branch with new-branch-name as name and contains all the code present in branch-name 

To modify branch-name
git branch -m <old-name> <new-name> 


Lets say you have not visited remote-branch/branch-which-you-have-not-visited 
git fetch origin <remote-branch>  --> For fetching changes this will not affect our local repository

git pull origin <branch> 

git stash 
git stash pop
git stash list
git stash clear --> For clearing all the stashes
git stash drop "$id"
