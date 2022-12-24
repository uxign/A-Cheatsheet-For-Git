# A-Cheatsheet-For-Git
## Here is a cheat sheet for some commonly used Git commands:

### Setup

git config --global user.name "Your Name": Set your name to be used as the commit author
git config --global user.email "your@email.com": Set your email to be used as the commit author

### Creating Repositories

git init: Initialize a new Git repository
git clone <repository>: Clone an existing repository

### Making Changes

git status: Check the status of your repository
git add <file>: Add a file to the staging area
git add . : Add all modified and new files to the staging area
git commit -m "message": Commit changes with a message
git reset HEAD <file>: Remove a file from the staging area

### Viewing History

git log: View the commit history
git diff: View changes that have not been staged
git diff --staged: View changes that have been staged

### Working with Remotes
git remote add <name> <url>: Add a remote repository
git push <name> <branch>: Push changes to a remote repository
git pull <name> <branch>: Pull changes from a remote repository

### Branching

git branch: List all branches
git branch <name>: Create a new branch
git branch -d <name>: Delete a branch
git checkout <name>: Switch to a branch

### Merging

git merge <branch>: Merge a branch into the current branch

### Stashing Changes
git stash: Stash changes
git stash list: View a list of stashes
git stash apply: Apply the latest stash
git stash drop: Discard the latest stash

### Tagging

git tag <tagname>: Create a new tag
git tag -a <tagname> -m "message": Create a new tag with a message
git tag -d <tagname>: Delete a tag
git push --tags: Push tags to the remote repository

### Reverting Changes

git revert HEAD: Revert the last commit
git revert <commit>: Revert a specific commit

### Resetting

git reset HEAD: Reset the staging area to the last commit
git reset --hard HEAD: Reset the staging area and working directory to the last commit
git reset --hard <commit>: Reset the staging area and working directory to a specific commit

### Aliases

git config --global alias.<alias_name> <git_command>: Create aliases for commonly used commands
