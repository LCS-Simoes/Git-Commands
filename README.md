<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="100" height="100" />
</p>

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

Observation:
When you do a git push with the -u option, you are telling Git to associate the local branch with the remote branch you are pushing.
This makes it easier to use commands like git pull and git push in the future, as Git already knows which remote branch to associate with the local branch.
````

