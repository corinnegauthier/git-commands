# Git Cheat Sheet


A little list I've put together while learning git & gh commands. I've also included commands used to install git via cli ☺️


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

|   Command                                  |       Description                                                                |
| -------------------------                  | -----------------------------
| git config --global user.name [username]   |  sets your username in git (does not need to be the same as your github username)|
| git config --global user.email [email]     |  sets your commit email address in git                                           |
| gh auth login                              |  used to set up your authentication token                                         |


# Creating & Managing Repositories 

| Command                                      |  Description
| ------------------------------------------   | -----------------------------                                                              |
| gh repo create                               |  creates a new repository                                                                  |
| git add [file name]                          |  creates a new file (if the file name has spaces wrap in quotation marks(i.e; "file name") |
| cd [folder name] && git init && git add .    |  adds the contents of an entire folder                                                     |
| git commit                                   |  saves the changes made to the repository                                                  |
| git push                                     |  uploads content to remote repository                                                      |
| git fetch                                    |  downloads content from remote repository                                                  |
| gh repo view [repo name]                     |  view contents of repository  
