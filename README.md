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
  git add README.md ~~> 
  It's not mandatory, But it's good
  git commit -m "first commit"
  git branch -M main 
  git remote add origin https://github.com/linktoyourrepository.git
  git push -u origin main
````

