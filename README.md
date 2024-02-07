# Github Simple Terminal Commands

Optional:
- cd C:\...                               // Switch to destination path. <br />
- git status                              // Check tracked and untracked project files and the changes. <br />
<br />
Steps: <br />
1) Push the Project to Github
git checkout -b "branch name"             // Create new branch and switch the path to created branch. <br />
git add .                                 // Select all files in the project. <br />
git commit -m "message"                   // Add command into changed files. <br />
git push origin "branch name"             // Push changes files to created branch in Github. <br />
<br />
3) Create Pull Request in Github <br />
Go to Github <br />
Click "New Pull Request" <br />
Click "Create Pull Request" <br />
<br />
4) Merge with Master Files <br />
Click "Merge Pull Request" <br />
Click "Confirm" <br />
Click "Delete Branch" <br />
<br />
6) Pull the Merged Files from Github <br />
git checkout master                        // Switch back to master branch. <br />
git pull                                   // Pull the merged files from Github to local. <br />
git branch -D "branch name"                // Delele created branch in local. <br />
