<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="100" height="100" />
</p>

# Observations

````
Branch: In Git, a "branch" is an independent line of development. You can create new branches from an existing
branch to work on new features or fixes without directly interfering with the main branch (typically called master or main).
-u (upstream): This parameter is used to set the "upstream" of a branch. The upstream is the remote repository
and remote branch that your local branch should be pushed to and pulled from for updates.
-m (move): This parameter is used to rename a branch locally. You can use -m followed by the current branch name and the
new name to rename it.
A "fork" on GitHub refers to the action of creating a copy of a user's repository into your own GitHub space. When you fork
a repository, you essentially duplicate the original repository into your own GitHub account.
This allows you to work independently on your own fork without affecting the original repository.

````
# Starting versioning in a repository

````
  echo "#Repositoryname" ~~>  README.md
  git init
  git add README.md ~~> It's not mandatory, But it's good
  git commit -m "first commit"
  git branch -M main 
  git remote add origin https://github.com/linktoyourrepository.git
  git push -u origin main
````

# Common commands

````
  git add [file] ~~> Adds a file to the index (staging area) for the next commit
  git commit -m "message" ~~> Commits the changes added to the index, with a message
  git status ~~> Shows the current state of the repository
  git diff ~~>  Shows differences between modified files and the last commit.
  git pull ~~> Pulls (downloads and merges) changes from the remote repository to the current branch
  git push origin ~~> Pushes commits from the local repository to the remote repository named "origin
  git fetch ~~>  Retrieves updates from a remote repository without merging them.
  git checkout -- . ~~> Discards changes in the working directory and restores files to their last committed state.
````
# Advanced commands


