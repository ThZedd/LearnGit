# Learning Git Commands 

#### This repository was made to put some git commands

```` 
git clone --> Command to clone a git repo from a remote server or github

git status --> Command to change the current status of the branch and to know the state of changes i.e. Modified, Staged or Committed State

git log --> Command to see the last 'N' git commits on the branch

git add <file name> --> Command to add the changes from Modified State to the Staged State

git restore --staged <file name> --> Command to restore the file in original state by discarding all the changes or change the file from staged state to modified state

git commit -m "Message Text in here" --> Command to commit the changes to the local branch which was cloned using git clone

git remote -v --> We use this command to know the origin of our repository

git push origin main --> Command to push our changes to a destination which can be a remote server or Github

git branch <name of the branch> -- Command to create a new branch

git branch -a --> Command to see all the branches that you have (the branch that you are on will have a * before the name of the branch, example: *main)

git checkout <name of the branch> --> Command to switch to the branch that you want

git branch -D <name of the branch> --> Command to delete the branch you want if, didnt merge it (make sure you are on a different branch to delete the other)

git merge <name of the branch> --> Command to merge branches together (to use this make sure that you are on the right branch that you want the other branches to merge to)
````




