# Prep Work Notes

## Git

### Git Commit

`git commit`

### Git Branch

`git branch 'branch-name` - Create Branch

`git checkout <name>` - Puts us on the new branch before commiting

`git checkout -b <branchName>` Create new branch **AND** Check it out at the same time.

### Branches &amp; Merging

`git merge` -

`git merge <name>` - merge one branch into another.

`git checkout <name1>; git merge <name2>` - Puts us on Name1 branch, and merges name 1 into name 2.

Make a new branch called bugFix
Checkout the bugFix branch with git checkout bugFix
Commit once
Go back to main with git checkout
Commit another time
Merge the branch bugFix into main with git merge

### Rebase

`git rebase <name>` Combining work between branches

Checkout a new branch named bugFix
Commit once
Go back to main and commit again
Check out bugFix again and rebase onto main
