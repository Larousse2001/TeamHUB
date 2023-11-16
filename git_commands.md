## Git Commands

### Create and Switch to Another Branch
```bash
# Create a new branch
git branch user/add-sudoku-features

# Switch to the new branch
git checkout user/add-sudoku-features

# Make changes and stage them
git add .

# Commit the changes
git commit -m "Your commit message"

# Switch to the main branch
git checkout main

# Pull the latest changes from the main branch
git pull origin main

# Switch back to the feature branch
git checkout user/add-sudoku-features

# Rebase changes on top of the main branch
git rebase main

# Resolve conflicts if any and continue rebase
git rebase --continue

# Switch back to the main branch
git checkout main

# Merge the feature branch into the main branch
git merge user/add-sudoku-features

# Push the changes to the main branch
git push origin main

# Remove test.txt from the resources directory
cd resources
git rm -f test.txt

# Remove test.txt from the sources directory and clean untracked files
cd ./
cd sources
git rm -f test.txt
git clean -nfd

# Set up aliases for common commands
git config --global alias.ck checkout
git config --global alias.ci commit
git config --global alias.br branch

# List global git configurations
git config --list

# Configure autocorrect for git commands
git config --global help.autocorrect 1

# Cherry-pick a specific commit from another branch
git cherry-pick <commit-id>

# Show the reflog for the feature branch
git reflog show user/add-sudoku-features

# Display commit history in one line
git log --oneline

# Enjoy *__*
