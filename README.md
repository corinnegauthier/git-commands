# Git Cheat Sheet


A little list I've put together while learning git & gh commands. I've also included the commands used to install git & github cli ☺️


# Installation

|        Command                              |       Description                                                               | 
| ------------------------------------------- | -----------------------------------------------                                 |   
| brew install git                            |  installs git on macOS                                                          |
| apt install git                             |  installs git on debian or ubuntu based linux distributions               
  pacman -S git                               |  installs git on arch linux                                                     |
| brew install gh                             |  installs github CLI on macOS 
| apt install gh                              |  installs github CLI on debian or ubuntu based linux distributions              |
| pacman -S gh                                |  installs github CLI on arch linux
                


# Initial Set Up

|   Command                                  |       Description                                                                        |
| -------------------------                  | -----------------------------
| git config --global user.name [username]   |  sets your username in git (does not need to be the same as your github username)        |
| git config --global user.email [email]     |  sets your commit email address in git                                                   |
| gh auth login                              |  used to set up your authentication token                                                |


# Connecting to Remote Repository

| Command                                                                       |  Descriptions                                                                  |
| -----------------------------------                                           |    -------------------------------------------
| git remote set-url [repo name] `https://github.com/username/repository.git`   |   connect to remote repository via https protocol           |                            
| git remote set-url [repo name] `git@github.com:username/repository.git`       |   connect to remote repository via ssh protocol             |                               


# Creating & Managing Repositories 

| Command                                      |  Description
| ------------------------------------------   | -----------------------------                                                              |
| gh repo create                               |  creates a new repository                                                                  |
| git add [file name]                          |  creates a new file (if the file name has spaces wrap in quotation marks(i.e; "file name") |
| cd [folder name] && git init && git add .    |  adds the contents of an entire folder                                                     |
| git commit -m [commit message]               |  saves the changes made to the repository with a git commit message                        
| git push                                     |  uploads content to remote repository    
| git -f push                                  |  force uploads content to remote repository                                                |
| git pull                                     |  updates the remote repository                
| git fetch                                    |  downloads content from remote repository 
| gh repo view [repo name]                     |  view contents of repository  
