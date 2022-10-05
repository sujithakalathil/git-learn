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
2. 