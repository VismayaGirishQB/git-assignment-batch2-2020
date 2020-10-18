# **BASIC COMMANDS IN GIT**
### Configure the author name and email address to be used with your commits:
* [git config --global user.name "Name" e.g; git config --global user.name "Sam Smith"]
* [git config --global user.email "email" e.g; git config --global user.email "sam@gmail.com"]
### Create a new local repository:
* [git init <repo_name> e.g; git init newrepository]
### Create a working copy of a local repository:
* [git clone /path/to/repository e.g; git clone https://github.com/VismayaGirishQB/git-assignment-batch2-2020.git]
### For a remote server, use:
* [git clone username@host:/path/to/repository e.g; git clone username@host:/path/to/repository]
### Add one or more files to staging :
* [git add <file_name> e.g; git add 123.txt] 
* [git add *  This add all the files in the repo]
### Commit changes to head (but not yet to the remote repository):
* [git commit -m "Commit message"]
### Commit any files you've added with git add, and also commit any files you've changed since then:
* [git commit -a]
### Send changes to the master branch of your remote repository:
* [git push origin master]
### List the files you've changed and those you still need to add or commit:
* [git status]
### If you haven't connected your local repository to a remote server, add the server to be able to push to it:
* [git remote add origin <server>]
### Create a new branch and switch to it:
* [git checkout -b <branchname> e.g; git checkout -b develop  (here develop is the new branch)]
### Switch from one branch to another:
* [git checkout <branchname> e.g; git checkout develop]
### List all the branches in your repo, and also tell you what branch you're currently in:	
* [git branch]
### Delete the feature branch:	
* [git branch -d <branchname> e.g; git branch -d develop]
### Push the branch to your remote repository, so others can use it:	
* [git push origin <branchname> e.g; git push origin develop]
### Push all branches to your remote repository:
* [git push --all origin]
