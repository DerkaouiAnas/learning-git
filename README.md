# GIT cheatsheet

`git init .` initializing git repository

`git status` shows the current state of the git working directory and staging area

`git add .` add all the files in the current directory into the staging area

`git reset {filename}` undo `git add {filename}`

`git reset` to unstage all changes for all files

a commit is a save point

`git commit -m "commiting message"`   -> this will save the current state of the working directory (after adding them to the staging area) 

`git log` -> to see changes that we have commited

`git show {hashcode of the commit}` -> to see changes by the commit

`git diff` -> give the difference between the current working directory and what has been committed

`git restore {filename}` -> discard changes on a file  (if modified after a commit)

`git commit --amend -m "message"` -> this will amend (modify) the commit message



## git remote

`git remote add {name} {url}`   -> create new remote called {name} (usually named as __origin__) that represents the {url} (we can push to {name} instead of typing the complete {url})

`git branch -M main`    -> force move/rename a branch

`git push -u {remote} {branch}`     -> push the current branch into remote repository