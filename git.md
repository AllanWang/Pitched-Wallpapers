# Git Cheat Sheet

View a sample .gitignore file [here](https://github.com/asdfasdfvful/Pitched-Wallpapers/blob/master/.gitignore)

*words in italic represent things you should change (ie message = what you should type as your message)*

|Initializing||
:---|:---
git init | initializes .git
git add -A | adds all the git files
git commit -m *message* | creates a commit with a message (message is mandatory)
git push origin master|pushes to origin
git pull origin master|pulls from origin

|Forceful Actions||
:---|:---
git push -f origin master|force pushes to origin (remote will be exactly like the origin, changes there will be lost
git pull -f origin master|force pull from origin
git reset --hard HEAD~*number*|will remove the latest *number* commits (ie 1 will remove 1 commit) permanently


|Remote||
:---|:---
git remote -v | view existing remotes
git remote add *name* *url* | add new remote with given url
git remote rm *name* | remove remote
git remote set-url --add --push *name* *url*| adds new push url to existing remote

|Other||
:---|:---
git clone [url] | clones the git url to local
