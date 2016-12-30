# TO remove any previous history of git commits and do a clean push

## Step 1: remove all history

`rm -rf .git`

## Step 2: reconstruct the Git repo with only the current content

`git init`

`git add .`

`git commit -m "Initial commit"`

## Step 3: push to GitHub.

`git remote add origin <github-uri>`

`git push -u --force origin master`

# git rename branch name

If you want to rename a branch while pointed to any branch, do :

`git branch -m <oldname> <newname>`
If you want to rename the current branch, you can do:

`git branch -m <newname>`
A way to remember this, is -m is for "move" (or mv), which is how you rename files.
