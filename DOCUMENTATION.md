***Udacity bikeshare git documentation ***

# link to remote repository
https://github.com/paul6ix/bikeshare

# entering my udacity directory on my desktop
cd ~/desktop/udacity/

# creating a new directory for my bikeshare project 
mkdir bikeshare

# entering my bikeshare directory 
cd bikeshare


# enabling version control in the folder
$ git innit

# checked the status of my repository
$ git status

# Added the file to my local repository and staged it 
$ git add bikeshare.py

# Configured my username
$ git config --global User.name "paul6ix"

# Configured my email
$ git config --global User.email "okporp@gmail.com"

# Comitted files
$ git commit -m "intial commit"

# Added the remote repository
$ git remote add origin https://github.com/paul6ix/bikeshare.git

# Verified the remote repository
$ git remote -v

# Pushed to remote repository
$ git push origin master

# created new branch for documentation
$ git branch documentation

# created new branch for refactoring
$ git branch refactoring
