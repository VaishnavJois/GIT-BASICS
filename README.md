# GIT-BASICS


## setting global user
### git config --global user.email
### git config --global user.name

## push declined due to email privacy restrictions
#### git config --global user.email {ID}+{username}@users.noreply.github.com
## reset author information on last commit
### git commit --amend --reset-author
###### https://stackoverflow.com/questions/43378060/meaning-of-the-github-message-push-declined-due-to-email-privacy-restrictions
## initializing repo
### git init

## after any modification in existing repo
### git add .
### git commit -m "commit text"

# for the first time
### git remote add origin <link> 

#
### git push -u origin master
#### -u = upstream so next time when you use 'git push', it defaults to git push origin master
## creating branch in git
### git pull
### git checkout <branch name>
## make changes 
### git commit -m "msg"
### git push 

### compare & pull request
### pull request
### merge pull request
### changes reflected to master


## Make .gitignore file.
### Run below commands in your terminal
#### git rm -r --cached node_modules
#### git commit -am "node_modules be gone!"
#### git push origin master

## Create custom branch
#### git checkout -b <BRANCH_NAME>
#### git push <REMOTE_NAME> <BRANCH_NAME>


## Unstage commit
#### git reset HEAD^
