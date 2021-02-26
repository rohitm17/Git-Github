## What is Git?
Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.
## Important terms

#### Repository:

It is the collection of files and folders (code files) that you’re using git to track.

#### Commit:

The "commit" command is used to save your changes to the local repository.

#### Push:

Pushing is essentially syncing your commits to GitLab.

#### Branch:

A branch is like a parallel world where you can create commit without introducing bugs into production code.

#### Merge:

Merge integrates two branches. When a branch becomes error free and is ready to become part of main branch, it is merged.

#### Clone:

Clone means making an exact copy on local machine.

#### Fork:

A fork is a copy of a repository that allows you to freely experiment with changes without affecting the original project.

## Practical work
### How to Install Git

For Linux, open the terminal and type 
```
sudo apt-get install git 
```
On Windows, it’s just as simple. You [download the installer](https://git-scm.com/download/win) and run it.

# Starting a project

git init 'project name'
git clone 'project url'


### Add a file to the staging area

git add 'file'

### Remove file from directory

git rm 'file'

### Create new branch

git branch 'name'

### Status of working directory

git status

### Commit to local

git commit -m "comment"

### List all local branches

git branch -a

### Switch current branch to specified one

git checkout -b 'branch_name'

### Remove selected branch

git branch -d "name"

### Fetch changes from the remote

git fetch 'remote'

## Git Internals 


![shortcut](https://github.com/rohitm17/Git-Github/blob/main/Git.png)

The picture above shows you the basic commands to move your files into different
trees in your repository.
<hr>

&nbsp;

&nbsp;
### Thanks for Reading!!!
