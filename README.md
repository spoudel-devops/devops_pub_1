# devops_pub_1 class
learning git from github


git push origin :<branch name> : to delete a branch from remote repo ( example "git push origin :feature/task-1")


GIT COMMANDS

git init : to initilaize an empty reposity

git clone <repo url>: to clone the remote repository in to local machine
after cloning "cd reponame/directory"
Example : git clone https://github.com/spoudel-devops/devops_pub_1.git

git branch: 	to check which branch we are working on. 
git branch -a :	to display all the branches.

git checkout -b <branch name> : to create a NEW branch
Example : git checkout -b my-local-branch

git add . : to add the file (make the files in to tracking from untracked mode)

git commit -m "Commit message" : to create commit (version)

git push origin <branch name>: to push the local changes to remote repository for the respective branch.

git pull origin <branch name> : to pull the branch into the current branch.

git diff : to see the difference in local machine (this has to be performed before git add)

git status : to check the current status of the files in repo (like, untracked, added, any commits to be made)

git log : to view the commit information 

git push --set-upstream origin <branch name>
18db3a76fefa271aad8b0be5593969f2b6c70ec0
