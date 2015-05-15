#Week 1

##The Module Pattern
[Article explaining it](http://toddmotto.com/mastering-the-module-pattern/)

##Git stuff
###Adding a new branch from the terminal  
-b moves you onto the branch once you've created it  
`git checkout -b [name of new branch]`  
OR  
`git checkout --orphan [name of new branch]`  
###Deleting a branch
####Local
`git branch -d [name of branch]`
####Remote
`git push origin --delete [name of branch]`

###Renaming a branch
####Local
When on branch: `git branch -m [newname]`  
From another branch: `git branch -m [oldname] [newname]`  

###SSH key
https://help.github.com/articles/generating-ssh-keys/

##Testing
###Setting up a simple server
[http://www.linuxjournal.com/content/tech-tip-really-simple-http-server-python]
* localhost:8000/tests.html