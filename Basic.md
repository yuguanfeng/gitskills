# Basic knowledge and command of git
## Basic knowledge
> Repository in local computer or in github wesite

  *Repository is the basic unit of git. Through push or pull or remote, we can creat connection between local repository and remote repository.*

> Three parts of repository

  *The core framework is divided into three parts:Working Directory, Stage and Repository. The working directory is where we edit code. The stage is where we save the changes. The respository is where all done. Add from working directory to stage. Commit from stage to repository*

## Basic command
> git init

*creat a new repository.*

> git add

*add code from the working directory to the stage.*

> git commit -m "do what"

*commit code from the stage to the repository.*

> git diff

*tell the difference in the working repository, stage and repository. More usage can be found in git --help.*

> git reset HEAD~

*go back to the version which was committed before. Two thing were done. One is to make the repository head point to the last version, another is to overwrite the files of the last version of the repository to the temporary stage to discard the last commit.
But the files in working direcory are not overwritten.*

> git log<git log --oneline --decorate --all --graph>

> git status

> git check

> git branch

> git merge

> git clone

> git push origin master

> git pull origin master