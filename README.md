#This is my local repo


#Git Branches

![alt text](image.png)


git branch (to chech branch)

git branch -m main (rename branch)
git checkout -b <-new branch name-> ( to create new branch)
git branch -d <-branch name-> ( to delete branch)


Merging  Code

way1 

        git diff <-branch name->  (to compare commits, branches, files and more)

    git merge <-branch name ->


way2

create a PR(pull request)


Pull Request

-- it tells you tell others about changes you've pushed to a branch in a repository on githuib.


Pull Command

git pull origin main


used to fetch and dowload content from a remote repo and immediately updtate the local repo to match that content



Undoing changes

case 1: staged changes

    git reset <-file name ->

    git reset

case 2: commited changes ( for one commit)

    git reset HEAD~1


case 3: commited changes ( for many commits)

    git reset <-commit hash->
    git reset --hard <-commit hash ->