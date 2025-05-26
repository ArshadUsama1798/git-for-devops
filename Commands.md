Repository Management
git init                       # Initialize a new Git repository
git clone <repo-url>          # Clone an existing repository
git remote -v                 # Show remote URLs
git remote add origin <url>   # Add a new remote repository

Working with Changes
git status                    # Check status of files
git add <file>                # Stage a specific file
git add .                     # Stage all changes
git restore <file>            # Discard changes in a file
git diff                      # Show unstaged differences
Committing Changes
git commit -m "Message"       # Commit staged changes with a message
git commit -am "Message"      # Add & commit tracked files in one step
Branching
git branch                    # List all branches
git branch <name>             # Create a new branch
git checkout <branch>         # Switch to a branch
git checkout -b <name>        # Create and switch to a new branch
git branch -d <name>          # Delete a branch

