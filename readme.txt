# Initialize a new Git repository
git init

# Add files to staging area
git add . # Add all files
git add <filename> # Add specific file

# Commit changes with a descriptive message
git commit -m "description of changes"

# Add remote repository
git remote add origin <repository-url>

# Push changes to remote repository
git push -u origin master/main # For main branch
git push -u origin <branch-name> # For other branches

# Clone an existing repository
git clone <repository-url>

# Pull latest changes from remote
git pull # Update local repository with remote changes