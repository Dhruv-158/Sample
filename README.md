# Initialize a new Git repository
git init

# Add a file (README.md in this case)
git add README.md

# Commit the changes with a message
git commit -m "first commit"

# Rename the current branch to 'main'
git branch -M main

# Add a remote repository (your GitHub repository)
git remote add origin https://github.com/Dhruv-158/React-Projects.git

# Push the changes to the remote 'main' branch
git push -u origin main

# Change the remote URL (if necessary)
git remote remove origin
git remote add origin <new-url>
git remote -v

# Push again after changing the remote
git push origin main

# Clone a repository from GitHub
git clone <repository-url>

# Check the status of your working directory
git status

# Branch-related commands
git branch                    # List all branches
git branch -M main             # Rename branch to 'main'
git checkout <branch-name>     # Switch to another branch
git checkout -b <new-branch>   # Create and switch to a new branch
git branch -d <branch-name>    # Delete a branch

# Merge branches
# If you're on a branch and want to merge its changes into 'main'
git merge <branch-name>

# Pull remote changes into your local repository
git pull origin main

# Reset a file to its last committed state (discard local changes)
git reset <file-name>
git reset

# Undo the last commit (soft reset)
git reset HEAD~1

# Show commit history
git log

# Reset to a specific commit
git reset <commit-hash>

# Hard reset to a specific commit (this will overwrite local changes)
git reset --hard <commit-hash>

# Fork: Take someone else's repository into your own GitHub account
# (done through GitHub UI)
