# Text Analytics exam project

### Git Commands

#### Init folder
Navigate to desired folder and init in that folder:<br>
Git init

#### Connect to repository (only once)
git remote add origin https://github.com/falkenovergaard/TA_Exam.git (connect to repository)<br>
git remote -v (Verifies the new remote URL)<br>

#### See branches and checkout branch
git branch <br>
git checkout "branch name"<br>

#### Pull branch (download)
git pull origin "branch name" (fetch and merge) <br>


#### Commit and push to a branch
git add . (Adds files to the commit)<br>
git commit -m "First commit" (take the added files and commits with a message)<br>
git push -u origin "branch name" (pushes to the remote)<br>

#### Merge master with branch
git checkout master<br>
git pull origin master<br>
git merge "branch name"<br>
git push origin master<br>



