# Configuration Commands 

git --version                # Check Git version  
git config --global user.name "Your Name"  # Set Git username  
git config --global user.email "you@example.com"  # Set Git email  
git config --global --list   # Show Git configuration  


# Working with Repositories

git init                     # Initialize a new Git repository  
git clone <repo_url>         # Clone an existing repository  
git remote -v                # View remote repositories  
git remote add origin <url>  # Add a remote repository  
git remote set-url origin <new_url>  # Change remote repository URL  


# Staging and Committing Changes

git status                   # Check the status of your repository  
git add .                    # Stage all changes  
git add <file>               # Stage a specific file  
git reset <file>             # Unstage a file  
git commit -m "Commit message"  # Commit staged changes  
git commit --amend -m "New message"  # Edit last commit message  


# Working with Branches

git branch                   # List all branches  
git branch <branch_name>     # Create a new branch  
git checkout <branch_name>   # Switch to a branch  
git checkout -b <branch_name>  # Create and switch to a new branch  
git merge <branch_name>      # Merge a branch into the current branch  
git branch -d <branch_name>  # Delete a branch  
git branch -D <branch_name>  # Force delete a branch  


# Pushing and Pulling from Remote Repositories

git pull origin main         # Pull the latest changes from remote  
git push origin main         # Push changes to remote repository  
git push -u origin <branch>  # Push a new branch to remote  
git push --force             # Force push (be careful!)  

