# GIT-LEARN
## 1. Commands
1. git init
    - Initialize the local git repository.
2. git add -A
    - Add all files from working directory staging area.
3. git add {file_name}
    - Add the file to staging area.
4. git commit -m "{message}"
    - To commit all the files from staging area.
5. git commit {file_name} -m "{message}"
    - Commit the file name to local repository with the message.
6. git remote add origin https://github.com/sujithakalathil/git-learn.git
    - Register the remote repository with local repository.
7. git push -u origin main
    - Push the changes from local repository to remote repository.
8. git diff {file_name}
    - Shows diffrences between files in working folder and staging area.
9. git diff --staged {file name}
    - Shows diffrences between files in staging area and local repository.
10. git branch -M main
    -  Renames the main branch as 'main'. This should be done soon after 'git init' is fired.

## 2. Branching & Merging

1. git log --oneline
    - To check if all branches are loking at the same commit or not.
2. git branch feature1
    - Create a branch named feature1. This will point to the local  commit point.
3. git switch feature1
    - Switches to the branch- feature1.
4. git merge feature1
    - Merge the main branch and feature1 branch. To do this you must on main branch.
5. git branch -d feature1
    - Delete the branch feature1. This can be done only once the changes are merged with main branch.
6. git branch --merged
    - Shows the branch which are merged.
7. git branch --no-merged
    - Shows the branch which are not merged.
8. git log --all --oneline --graph
    - Shows the graphical representation of all branches and commit points.
9. git log --oneline --all --stat   
    - Show the commit points and the stats.