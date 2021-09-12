# Git and Windows terminal Commands

## Windows Terminal Commands

```description
# Show paths in the folder 
dir

# Clear screen
cls

# Open folder
cd folder

# Exit of the folder
cd ..

# Create a folder
mkdir newfolder

# Delete folder
rmdir newfolder

# Delete file
del example.txt

```

## Git Commands

```description

# Return lasts commits
git reset --hard f414f31

# Create a clone in my local computer.
git clone https://github.com/williamcamasil/Desenvolvimento-WEB  

# Show the status of changes and not changes
git status

# Add all changes for finish steps
git add .

# Command that save the steps that were finished
git commit -m "arquivo readme"

# Send the changes for the repository
git push

# Ask to update with a new branche
git push --set-upstream origin feature/new-branche

# Recover the last change done in the repository of the chose branche
git pull 

# Update branchs
git fetch

# Show the log history
git log

# Delete branch from repository
git push origin --delete feature/modalContract

# Choose another branch to start using
git checkout feature/chooseBranche

# Create a new branch
git checkout -b feature/exampleBranche                   

# Ask merge to another branche
git merge feature/branche
  # after is necessary to ask push
  git push origin feature/branche

# Set email that i will use on repository
git config --global user.email "email@email.com"

# Set username that i will use on repository
git config --global user.name "williamcamasil" 

# Start local folder
git init

# Create a Readme.md
git add README.md

```
