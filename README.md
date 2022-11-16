# Simple CLI Command

Below is a list of CLI commands that we'll use occasionally

## Working with files and folders

```bash

# creating a folder
mkdir <folder-name>

# creating a file
touch <file-name>

# navigating through folders
cd <folder-name>

# going one step behind a folder
cd ..

# navigating back to the root folder
cd ~

# removing files and folders that have no permissions
rm <folder/file-name>

# removing files and folders that have permissions
rm -rf <folder/file-name>

# opening folder in VS code
code <folder/file-name/current dir>

# list all files within a folder
ls

# list all files within a folder with hidden
ls -a


## Basic git commands

```bash

# initializing local repository as git
git init

# adding files to local repository
git add .

# checking the status of the local repository
git status

# committing files to local repository
git commit -m "(Relevant message to changes)"

# pushing files to remote repository
git push

# creates copy of existing repository
git clone

# changing the branch
git checkout <branch-name>