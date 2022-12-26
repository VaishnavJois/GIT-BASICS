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

## 






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
