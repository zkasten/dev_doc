
Create Git repository

    git init

config

    git config --global user.name "(name)"
    git config --global user.email "(e-mail)"

check status

    git status

Add changes

    git add -A

Commit

    git commit -m "(comment)"

Check log

    git log

Reset(Hard)

    git reset (6 digit of commit to reset) --hard

Revert

    git revert (6 digit of commit)

Branch

    git branch (new branch name)

Show Branches

    git branch

Move to Branch

    git checkout (branch name)
    git checkout -b (branch name)   // create & move

Merge Branch

    git merge (branch name)

rebase

    git rebase (branch name)

Delete Branch

    git branch -d (branch name)

 Add Github Remote Repository

    git remote add __REMOTE__ _GITHUB_ADDR__

Check Remote Repository

    git remote

Commit to Github

    git push __REMOTE__ __BRANCH__

Clone Github Project

    git clone __REMOTE__

Check remote commit status

    git fetch

Update remote 

    git pull __REMOTE__ __BRANCH__
    
Check remote branch

    git branch -a

Create & Get remote Branch

    git checkout -b __BRANCH_NAME__ __REMOTE__/__BRANCH_NAME__

Delete remote Branch

    git push -d __REMOTE_NAME  __ __BRANCH_NAME__


