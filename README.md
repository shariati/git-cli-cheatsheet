is a version control system for tracking changes in computer files and coordinating work on those files among multiple people. It is primarily used for source code management in software development, but it can be used to keep track of changes in any set of files.

# How to use Git in Console
### View Version
Returns the version of installed Git
`git -version`

### Initialize Git
git-init - Create an empty Git repository or reinitialize an existing one
```
git init
```
https://git-scm.com/docs/git-init

### Git Status
Show the working tree status
```
git status
```
https://git-scm.com/docs/git-status

### Git Add
Add file contents to the index
```
git add <file/folder>
```
https://git-scm.com/docs/git-add

### Git Remove
Remove files from the working tree and from the index
`git rm —cached <file/folder>`
https://git-scm.com/docs/git-rm

### Git Commit
Record changes to the repository
```
git commit -m 'message'
```

add and commit (git commit -am '')
```
git commit -a -m ''
```

https://git-scm.com/docs/git-commit

### Git Push
Update remote refs along with associated objects
```
git push -u origin master
``` 
OR 
```
git push
```
https://git-scm.com/docs/git-push

### Git Add
Add file contents to the index
(would add all the files shown in git status)
```
git add .
```
https://git-scm.com/docs/git-add

### Git Diff
Show changes between commits, commit and working tree, etc
(see the difference)
```
git diff
```
https://git-scm.com/docs/git-diff

### Git Clone
Clone a repository into a new directory
```
git clone https://github.com/USER-NAME/REPOSITORY-NAME YOUR-FOLDER-NAME-YOU-WANT
```
https://git-scm.com/docs/git-clone

### Git Checkout
Switch branches or restore working tree files
```
git checkout BRANCH_NAME
```
https://git-scm.com/docs/git-checkout

### Git Log
Show commit logs
```
git log
```
https://git-scm.com/docs/git-log

### Git Branch
List, create, or delete branches
(to create branch from master)
```
git branch BRANCH_NAME
``` 
https://git-scm.com/docs/git-branch

### Git Config
Get and set repository or global options

```
git config —list (to see the git config)
git config —global user.name "CHANGE USER NAME"
git config —global user.email "CHANGE USER EMAIL"
```
https://git-scm.com/docs/git-config
