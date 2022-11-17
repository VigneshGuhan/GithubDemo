# Git Demo

## Installation Links:

### [Git](https://git-scm.com/downloads)
### [Github Desktop](https://desktop.github.com/)
### [Intellij Idea](https://www.jetbrains.com/idea/download/#section=windows)
### [Eclipse](https://www.eclipse.org/downloads/)


## Git Commands Used :


### To check version:
```
$ git --version 
$ git -v
```

### To update git locally:
```
$ git update
$ git update-git-for-windows
```

### Clone: 
```
$ git clone https://github.com/VigneshGuhan/GithubDemo.git
```

### Branching:

```
$ git branch
$ git branch branch1
$ git checkout branch1
```
or
```
$ git checkout -b branch2
```

### Staging:
```
$ git add .
```

### Status:
```
$ git status 
```

### Commit:
```
To commit but not stage:
$ git commit -m "<message>" 
```

```
To  commit and stage
$ git commit -am "<message>"
```

### View Staged File :
```
$ git ls-files
```

### Push the change:

```
$ git push
```

### Pull:
Fetch + merge = Pull
```
$ git pull
```

## Other commands:
### Init: 
To create a new Git repository
```
$ git init
```

### Difference : 
Find difference between current version and last committed version
```
$ git diff
$ git diff --staged
$ git diff firstbranch..secondbranch
```
To quit from vim click q

### Commit List :
Get list of all commits
```
$ git log
$ git log --oneline
$ git log --oneline --reverse
```
### Last Commit Details:
```
$ git show HEAD
```

### Help:
```
$ git –help
```

### Show Commit:
```
$ git show <commit id>
```


### Git Ignore Refrence:  [Github Ignore File](https://github.com/github/gitignore)

## Other Websites:
### [Git Explorer](https://gitexplorer.com/)
### [Git Tutorial from Bitbucket](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
