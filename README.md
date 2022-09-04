# GIT cheatsheet

`git init .` initializing git repository

`git status` shows the current state of the git working directory and staging area

`git add .` add all the files in the current directory into the staging area

`git reset {filename}` undo `git add {filename}`

`git rest` to unstage all changes for all files


a commit is a save point

`git commit -m "commiting message"`   -> this will save the current state of the working directory (after adding them to the staging area) 

`git log` -> to see changes that we have commited

`git show {hashcode of the commit}` -> to see changes by the commit

`git diff` -> give the difference between the current working directory and what has been committed

`git restore {filename}` -> discard changes on a file  (if modified after a commit)

`git commit --amend -m "message"` -> this will amend (modify) the commit message