# A-Cheatsheet-For-Git
## Here is a cheat sheet for some commonly used Git commands:

### Setup

1. git config --global user.name "Your Name": Set your name to be used as the commit author
2. git config --global user.email "your@email.com": Set your email to be used as the commit author

### Creating Repositories

1. git init: Initialize a new Git repository
2. git clone <repository>: Clone an existing repository

### Making Changes

1. git status: Check the status of your repository
2. git add <file>: Add a file to the staging area
3. git add . : Add all modified and new files to the staging area
4. git commit -m "message": Commit changes with a message
5. git reset HEAD <file>: Remove a file from the staging area

### Viewing History

1. git log: View the commit history
2. git diff: View changes that have not been staged
3. git diff --staged: View changes that have been staged

### Working with Remotes

1. git remote add <name> <url>: Add a remote repository
2. git push <name> <branch>: Push changes to a remote repository
3. git pull <name> <branch>: Pull changes from a remote repository

### Branching

1. git branch: List all branches
2. git branch <name>: Create a new branch
3. git branch -d <name>: Delete a branch
4. git checkout <name>: Switch to a branch

### Merging

1. git merge <branch>: Merge a branch into the current branch

### Stashing Changes

1. git stash: Stash changes
2. git stash list: View a list of stashes
3. git stash apply: Apply the latest stash
4. git stash drop: Discard the latest stash

### Tagging

1. git tag <tagname>: Create a new tag
2. git tag -a <tagname> -m "message": Create a new tag with a message
3. git tag -d <tagname>: Delete a tag
4. git push --tags: Push tags to the remote repository

### Reverting Changes

1. git revert HEAD: Revert the last commit
2. git revert <commit>: Revert a specific commit

### Resetting

1. git reset HEAD: Reset the staging area to the last commit
2. git reset --hard HEAD: Reset the staging area and working directory to the last commit
3. git reset --hard <commit>: Reset the staging area and working directory to a specific commit

### Aliases

1. git config --global alias.<alias_name> <git_command>: Create aliases for commonly used commands
