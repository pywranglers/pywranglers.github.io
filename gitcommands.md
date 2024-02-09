## BASIC GIT COMMANDS

The Git command to clone a Remote Repository to local Repository
-`git clone -b <branch name> <sshkey url>`
-`e.g. git clone -b master git@github.com:pywranglers/pywranglers.github.io.git`
-`e.g. git clone -b dev git@github.com:pywranglers/pywranglers.github.io.git`
-`e.g. git clone -b release git@github.com:pywranglers/pywranglers.github.io.git`

The Git command to create new branch 
-`git checkout -b <MyNewBranch>`
 
The Git command to check the status of repository / staging area / working directory
-`git status`

The Git add commands 
-`git add -u` - adds only changed files to the staging area -> untracked files will be ignored  
-`git add .` - adds all files (tracked or not) to the staging area

The Git commit commands
-`git commit -m "message here"`
-e.g.`git commit -m "Hello i have updated something or anything"`

The Git push commands
-`git push origin <branch name>` - push the changes in the branch name of your choice to origin remote repository
-e.g.`git push origin master`
-e.g.`git push origin dev`
-e.g.`git push origin release`
-e.g.`git push origin practice` 


## OTHER GIT COMMANDS

The Git command to initalize a local Repository to Github
-`git init` - initiate a repository

The Git command to configure an author of Repository
-`git config user.name "<John Doe>"`
-`git config user.email "<john@doe.org>"`