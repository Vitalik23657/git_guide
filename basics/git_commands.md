# Basic Git Commands

```bash
# Setup
git init          # create a new repository
git clone <url>   # download existing repository

# Check status
git status        # show current changes
git log           # show commit history

# Add & commit
git add file.txt  # stage specific file
git add .         # stage all changes
git commit -m "message"  # save changes with message

# Branching
git branch        # list branches
git switch -c new-branch  # create & switch branch
git switch main   # switch branch

# Update & share
git pull          # get latest changes
git push          # upload commits

# Undo basics
git restore file.txt          # discard changes in file
git restore --staged file.txt # remove from staging
```