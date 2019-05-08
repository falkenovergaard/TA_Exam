# Text Analytics exam project

## Git Commands

### Init folder and download
Navigate to desired folder:
Git init

### See branches and checkout branch
git branch
git checkout "branch name"

### Pull master
git pull origin master

### Commit and push to a branch
git add . (Adds files to the commit)
git commit -m "First commit" (take the added files and commits with a message)
git push -u origin "branch name" (pushes to the remote)

### Merge master with branch
git checkout master
git pull origin master
git merge "branch name"
git push origin master
