# Github Terminal Command
> [!TIP]
> <span title="Check tracked or untracked project files and the changes.">git status</span> 

## Steps
1. Push the Project to Github
    - <span title="Locate to destination file path.">cd C:\\...\\...\\...</span> 
    - <span title="Create new branch and switch targeted path to created branch.">git checkout -b "branch name"</span>
    - <span title="Select all files in the project folder.">git add . </span>
    - <span title="Add command on the changed files.">git commit -m "message"</span>  
    - <span title="Push changes files to created branch in Github.">git push origin "branch name"</span>

2) Create Pull Request in Github 
  - Go to Github 
  - Click "New Pull Request" 
  - Click "Create Pull Request" 

3) Merge with Master Files
  - <span title="Merge master file with current changes.">Click "Merge Pull Request"</span>
  - Click "Confirm"                            
  - <span title="Optional: Delete to avoid duplicate branch name, or can choose to save for backup purpose.">Click "Delete Branch"</span>

4) Pull the Merged Files from Github 
- Back to Software 
- git checkout master
> Switch back to main branch, default main branch usually named "Guideline".
- git pull                                 
> Pull the merged files from Github to local. 
- git branch -D "branch name"
> Delele created branch in local to avoid duplicate branch names, can choose to save for backup purposes. 

# Upload Large Files 
1) Install Upload Large File Github Command
2) Locate Large File
3) Upload to Github

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
