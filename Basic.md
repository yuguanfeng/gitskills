# Basic knowledge and command of git
## Basic knowledge
> Repository in local computer or in github wesite

  *Repository is the basic unit of git. Through clone/fetch, we can get repository from remote to local. Through pull, we can get files from remote to workspace. Through push, we can send repository from local to remote.*

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

*look over the record of every commit.The latter command is to show the abstract breifly.*

> git status

*show the status of this repository, like "Is there any new file in workspace not added to the stage(Untracked)?","Is there any changed file in workspace not added to the stage(Unstaged)?","Is there any changed file in stage not added to the repository(Uncommitted)?". When there is no new or changed file, it will show "nothing to commit, working tree clean".*

> git check

*have much functions the same as git reset*

> git branch

*create a new branch*

> git merge

*merge two branch*

> git clone

*get repository from remote to local.Both in http and ssh. And don't need to fill in user'name and email.*

> git push origin master

*push from local repository to remote repository.*


> git pull origin master

*pull from remote repository to local workspace.*

**pull and push through http need user's name and  password; ssh not need.**