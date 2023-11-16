# This Git Repository is to practice Git commands::

Steps to push the existing project to GitHub

1. Initial the Project as a Git 

	git init

2. git branch -M main (Suppose you want to Rename the current branch)

3. Go to the github.com and create a new repository

4. Now we need to add the remote to the Project

   git remote add origin <remote-url>   (remote url of the github repo)

5. To verify if the remote is added

   git remote -v

6. Now push the remote 

   git push -u origin main
########################################

# List of git commands

1. git remote -v
(The command is to check the remote add to the project)

2. git restore --staged .
(The command will restore all the add file)

3. git reset --soft HEAD^
(This command will revert the last staging commit which has not been pushed to staged area)

4. git reset --hard HEAD^
(This command will revert the last staging commit which has not been pushed and also remove all the changes made in the commit)

Steps to remove the file from the version control

1. git rm file.txt

2. git rm --cached file.txt

Approach second

Suppose you want keep the file but don't want the git to track

1. git rm --cached file.txt

2. put that file name in the .gitignore
