# Github_howto

1 - git init  

2 - git add .  
Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.

3 - git commit -m "First commit"   
Commits the tracked changes and prepares them to be pushed to a remote repository.   
To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.  

5 - git remote add origin remote repository URL   
Sets the new remote

6 - git remote -v  
Verifies the new remote URL

7 - go to GitHub desktop -> master -> Uncommitted Changes -> undo -> select files  

8 - Sync
