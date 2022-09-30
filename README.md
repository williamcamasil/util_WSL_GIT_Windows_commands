# WSL, Git and Windows terminal Commands

## WSL Ubuntu Terminal Commands

```description
# Show paths in the folder 
ls

# Show all hidden files 
ls -a

# Show all folders and files hidden or not
ls -la

# Back to home
cd

# Open folder 
explorer.exe .

# Enable new side prompt WSL command
alt + shift + t

# Clear commands from prompt
clear OR ctrl + l

# Create a folder
mkdir name_folder

# Delete folder or file
rm -r name_folder OR name_file

# Force delete folder or file
rm -rf name_folder OR name_file

# Create a file (^ = ctrl ex: ^+O save file) OR Open to edit file
nano name_file.txt

# Create a file 
touch name_file.txt

# Reload WSL without close prompt
source .extension_file

# Access adm environment and force commands  
sudo su

# Open file .zshrc to make configurations and put alias (shortcuts)
nano .zshrc

# Rename folder and file
mv Filename newFilename

```

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

# Create a file
echo > filename.txt

# Delete file
del example.txt

# Open selected folder
explorer .

```
More [commands](https://www.uniaogeek.com.br/guia-de-comandos-cmd-terminal-do-windows/) in Windows Terminal

## Git Commands

```description

# Remove all changes done
git stash

# Return lasts commits
git reset --hard f414f31

# Create a clone in my local computer.
git clone https://github.com/williamcamasil/Desenvolvimento-WEB  

# Show the status of changes and not changes
git status

# Add all changes for finish steps
git add .

# Bring lasts commits done [bring 7 characters from hash]
git hist

# Show changes of last commit
git show
OR # Show more than last commit
git show HASH1 HASH2 

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

# Show the log history [bring all characters from hash]
git log

# Delete branch from repository
git push origin --delete feature/modalContract

# Choose another branch to start using
git checkout feature/chooseBranche

# Create a new branch
git checkout -b feature/exampleBranch
OR
git checkout feature/exampleBranch

# Create a new branch from another branch
git checkout -c [master] [new-master]

# Rename branch
git branch -m [new-name]
  OBS: 
    - delete old branch with command: git push origin :old-name
    - send new name branch with command: git push -u origin new-name
    
# Ask merge to another branch
git merge feature/branche
  # after is necessary to ask push
  git push origin feature/branche

# Set email that i will use on repository
git config --global user.email "email@email.com"

# Set username that i will use on repository
git config --global user.name "williamcamasil" 

# Logout from your account in repository
git config --global --unset user.email
git config --global --unset user.name 

# Start local folder
git init

# Create a Readme.md
git add README.md

# Delete branch locally
git branch -d localBranchName

# Delete branch remotely
git push origin --delete remoteBranchName

# First push for the remotely branch
git push --set-upstream origin [branch-name]
OR
git push -u origin [branch-name]

# Useful command to bring only commits that you want to your branch
git cherry-pick f13bd3c3531f26e805c606729857f39987a2420f

# Remove last commit
git reset --soft HEAD~1

# List all branch (local and tracking)
git branch -a

# Show url remotely branch 
git remote get-url origin

```
