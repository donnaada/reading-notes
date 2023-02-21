# 🗒️ Class 03: Revisions and the Cloud

## The ACP Process: **A**dd, **C**ommit, **P**ush

- A : `git add .`
- C : `git commit -m "Why I changed code"`
- P : `git push origin master`

---

## What is Version Control?
Version Control is a system that allows the user to see all changes made to a file or set of files. Additionally, a user can choose to revert back to the previous or older version of a project.

## What is `cloning` in Git?
Cloning a repository is another way of saying creating a copy. Not only are the files copied, but all the versions of the project as well.

## GIT is NOT GITHUB
### What is Github?
Github is a place to share code with others and a place to store code. GitHub uses Git to help manage teamwork.

## Repository
A Collection of files that we have told GIT to keep track of. Usually one project is just one repo. Really Large projects might have multiple repositories for different parts ie front end vs back end. Repos can live on GitHub and/or the local computer

## What is a commit
Commits are the GIT equivalent of a `Save As...`. Each commit represent a successive version of the project.

## What is the command to track and stage files?
If we are only wanting to track ***one file***, the command we would use is `git add filename`. 

To track ***ALL*** files, use command `git add .` 

## What is the command to send your changed files to Github?
One we are done tracking and staging files, you must commit the file and/or changes made and the push.

> Commiting a file and add message can be done using the following code `git commit -m "commit comment goes here".`
To commit all changes made, enter the following code `git push origin master`

---

## Follow Along

`git remote -v` - see the URL of the GitHub repo
`git status` - current status of our files

### Cloning a Repo
1. get URL
2. `cd` into where we want the repo to go
3. `git clone (url)` to clone. Make sure to get the link from the green `<> Code` Button 


