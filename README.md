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
  echo "#Repositoryname" ⮕ README.md
  git init
  git add README.md ⮕ It's not mandatory, But it's good
  git commit -m "first commit"
  git branch -M main 
  git remote add origin https://github.com/linktoyourrepository.git
  git push -u origin main
````

# Common commands

````
  git add [file] ⮕ Adds a file to the index (staging area) for the next commit
  git commit -m "message" ⮕ Commits the changes added to the index, with a message
  git status ⮕ Shows the current state of the repository
  git diff ⮕ Shows differences between modified files and the last commit.
  git pull ⮕ Pulls (downloads and merges) changes from the remote repository to the current branch
  git push origin ⮕ Pushes commits from the local repository to the remote repository named
  git fetch ⮕  Retrieves updates from a remote repository without merging them
  git checkout -- . ⮕  Discards changes in the working directory and restores files to their last committed state
````

# Git Branch

````
  git branch -a ⮕ Lists all branches, both local and remote
  git branch -b [branch-name]  ⮕ creates a new branch named
  git branch -d [branch-name]  ⮕Deletes a local branch (use with caution)
  git branch -m [branch-name] [newBranchName] ⮕ Renames the current branch (use with the new branch name)
  git branch -m [newBranchName]
  git branch -M  ⮕ Force renames a branch, even if the new name already exists
  git checkout [branch-name] ⮕ Switches to a different branch or restores files
  git checkout -b [branch-name] ⮕ Creates and switches to a new branch named 
  git merge [branch-name] ⮕ Merges changes from another branch into the current branch
  git push origin Pushes [branch-name] ⮕ commits from the local branch to the remote repository named "origin
```` 

# Advanced commands

````
  git rebase [branch-name] ⮕ Reapplies commits from one branch onto another.
  git cherry-pick [commit hash] ⮕ Applies changes from a specific commit onto the current branch.
  git diff -stagged  ⮕ Shows differences between the last commit and what is staged for the next commit
  git reflog   ⮕ Displays the history of HEAD references, useful for recovering lost commits
  git stash ⮕  Temporarily stores changes so you can work on something else
  git stash pop ⮕  Restores changes that were saved with git stash
  git revert [commit-hash] ⮕ Creates a new commit that undoes the changes made by a previous commit
````

#SSH
````
  https://docs.github.com/en/authentication/connecting-to-github-with-ssh
````

# Differences between Git, GitHub and Git Bash 😵
````
Git
What it is: Distributed version control system
Main Function: Manage and version code locally
Example Commands: git init, git commit, git push

GitHub
What it is: Online platform that hosts Git repositories
Main Function: Facilitate collaboration and project management with Git on the web
Features: Online repositories, pull requests, and CI/CD integration

GitBash
What it is: Terminal for Windows with Unix and Git command support
Main Function: Execute Git and Unix commands on Windows
Features: Command-line interface for Git and Unix-like commands
````
