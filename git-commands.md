# Git Commands
## Setup
- sudo apt install git :- to install git if not already installed
- git --version :- to verify wheather git is installed and of what version
## Configuration
- git config user.name '<user_name>' :- command used to configure username
- git config user.email '<user_email>' :- command used to configue email
- git config :- to verify the configuration
## Basic Workflow
- git init :- used to make a directory a git repo
- git add :- to add a untracked file to staged (adding a file so that git can track it)
- git commit -m "message" :- to commit a file with commit history
## Viewing changes
- git status :- gives the status of git repo like on which branch currently we are
- git log :- to view the commit history
- git log --oneline :- to view commit history in compact manner
## Removing a file from staging area
- git rm <file_name> :- removes file from staging area and make it untracked 
## Branching commands
- git checkout <branch_name> :- to switch from one brach to other while using command the commit history will also be copied
- git checkout -b <branch_name> :- creates and switches to a new branch 
- git switch <branch_name> :- this command switches from one branch to another which is already existing
- git branch :- to list the branches in our repo
- git branch -D <branch_name> :- deletes the branch
