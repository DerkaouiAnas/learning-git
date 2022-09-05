# GIT cheatsheet

`git init .` initializing git repository

`git status` shows the current state of the git working directory and staging area

`git add .` add all the files in the current directory into the staging area

`git reset {filename}` undo `git add {filename}`

`git reset` to unstage all changes for all files

a commit is a save point

`git commit -m "commiting message"`   -> this will save the current state of the working directory (after adding them to the staging area) 

`git log` -> to see changes that we have commited

`git log --oneline`   -> to see changes in breaf

`git show {hashcode of the commit}` -> to see changes by the commit

`git diff` -> give the difference between the current working directory and what has been committed

`git restore {filename}` -> discard changes on a file  (if modified after a commit)

`git commit --amend -m "message"` -> this will amend (modify) the commit message



## Git remote

`git remote add {name} {url}`   -> create new remote called {name} (usually named as __origin__) that represents the {url} (we can push to {name} instead of typing the complete {url})

`git branch -M main`    -> force move/rename a branch

`git push -u {remote} {branch}`     -> push the current branch into remote repository

`git pull`      -> copy the commit on the remote to the local working directory


## Git brannches

`git branch`    -> to know the branch that you are on (in local)

`git branch -r`     -> to know the list of branches in the remote server

`git branch -a`     -> check all branches

`git branch {branch_name}`  -> create branch {branch_name} based on the current branch

`git checkout {branch_name}`     -> switch to the branch {branch_name}

`git chekcout -`     -> switch back to the previous branch



## steps of adding a feature

- create a branch with feature_name
- commit the changes
- push to the remote
- do a pull request
- merge the branch with the main
- delete the branch from the remote and from the local 
