Git Commands
============

### Getting Started

`git init`

Initialize a local git repository 
Creates an empty Git repository - basically a `.git` directory with subdirectories for objects, refs/heads, refs/tags, and template files.

`git clone <GIT_URL>`
Clone a repository into a new directory with same name as the remote repo

`git clone <GIT_URL> <DIR_NAME>`
Clone a repository into a DIR_NAME directory


### Basic Snapshotting

`git status`
Show the working tree status

`git add <FILE_NAME>`
Add a file to the staging area

`git add .`
Add all files to the staging area

`git add -A`
Add all new and changed files to the staging area

`git commit -m "<COMMIT_MESSAGE>"`
Commit changes with a message

`git rm -r <FILE_NAME>`
Remove a file (or folder)

`git reset <COMMIT_ID>`
Reset current HEAD to the specified state

`git reset <COMMIT_ID> --hard` :warning:
Hard reset current HEAD to the specified state


### Inspection and Comparison

`git log`
Show commit logs

`git log --oneline`
Show commit logs with only commit hash and title

`git diff`
Show changes between commits, commit and working tree, etc.
By default, shows comparison against HEAD(or since the last commit) across the entire repository.

`git diff <FILE_PATH>`
Show changes on the specified file in working tree

`git diff REF1 REF2`
Compare files between two different commits
Refs are HEAD, tags, branch names, and commit ID

`git diff BRANCH_1 BRANCH_2 FILE_PATH`
Compare a specific file across branches


### Additional Commands

`git clean -fdx` :warning:
Remove untracked files from the working tree


## References

1. Git Reference https://git-scm.com/docs/git
2. Atlassian Docs https://www.atlassian.com/git/glossary