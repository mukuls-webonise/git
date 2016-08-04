Installation

For linux : sudo apt-get install git

Configuration

git config --global user.name "Mukul"
Sets username


git config --global user.email "mukul.sharma@weboniselab.com"
sets email

git config --global color.ui auto
Use colors in terminal

git config --global auto.crlf input
Cross platform end lines selp

Create repo

git init [project-name-here]

git clone [url]
Clone existing repo from remote url

Make Changes

git status
Lists all new or modified files to be committed

git diff
Shows file differences not yet staged

git add [file]
Snapshots the file in preparation for versioning

git diff --staged
Shows diff bw staging and last file version

git reset [file]
Unstage the file

git commit -m "Message for commmit"

Branching

git branch
Lists all branches

git branch [name]
Creates branch with given name

git checkout [branch-name]
Checout to branch

git checkout branch -b [name]
Create branch and checkout to it

git merge [branch]
Merge branch

git branch -d [name]
Delete branch

Refractoring

git rm [file]
Delete file from dir and remove from staging

git rm --cached [file]
Preserve in dir but delete from git

git mv [old] [new]
Chnage file name

Save fragments

git stash
Temporarily store modified files

git stash pop
Restores most recent stash

git stash list
List all stash

git stash drop
Discard most recent stash

Review History

git log
Show log of commits

git diff [branch 1] [branch 2]
Shows content diff in branch 1 and 2

git show [commit]
Shows commit info

Reset

git reset [ccommit]
Undo all commits afer given commit, Working dir stays same

git reset --hard [commit]
Discard all history and go back to original commit

Synch

git fetch [dest]
Download all history from dest

git merge [dest] [src]
Combine src content into dest

git push [branch]
Upload contents of branch to origin

git pull
Download history and merge
