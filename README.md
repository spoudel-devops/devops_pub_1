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

git branch -d <branch name> : to delete the branch from local repository.

Note : the difference between git fetch and git pull are, git fetch will update the refences in local repo with remote repo ( example : if any new branch created. or any branch is updated with new commits)
where as git pull will update the current content/changes


create merge conflict scneria:

1. create branch task-1 from master.

2. create branch task-2 from master.


3. change a file on task-1 (local).

4. change the same file from task-2 (remote.local)

5. merge tasks-1 to master (local, remote).

6. task-2 to master.

fix : git pull origin master in to your tasks-2 branch

delete << and >> === lines
