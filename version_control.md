# Source Control

In order to manage your own code and share code with others you need to use source control.

## Git
Git is the standard version control system for open source and professional projects.  It is a distributed system (@todo expand).

You can view our projects on [Github/CodeHub](https://github.com/CodeHubOrg/)

Using git is easy once you know how!  You just need to know the basic concepts and commands to get going.

[Useful Git techniques + other resources
](https://github.com/CodeHubOrg/discussions/issues/12)

A great way to learn is by doing a workshop.  Open a terminal window and type the following:
```
npm install -g git-it
git-it
```
## Installation
```
sudo apt-get install git

```

## How to download code
So you've seen a great project on github repository and you want to download a working copy and take a closer look.  This is called 'cloning the repo'.  Go to the repo github page click the 'clone or download' green button and copy the link.  Then enter the following command:

```
git clone https://github.com/CodeHubOrg/organisations-database.git
```

This will download the code to a directory called organisations-database, you can add a custom directory name as an additional parameter if you need to.

## How to save your code
```
cd [your project path]
git init 
git add .
git commit -am 'Initial Commmit'
```
Then create a repo on your github account and follow the instructions to push your changes.

## Branches are cheap!
Branches are cheap so use them.  For example if you want to play about with a new feature or do a bug fix.

## Useful commands
```
git clone [url] - clone a git repo
git init - intialise git repo
git log - show log
git status -s - show working directory status
git checkout [branch] - check out a branch
git checkout -b [branch] - make a new branch based on current branch
git add . - add all files
git add -u - add deleted files
git commit -am "[commit message]" - add and commit with message
git push [remote] [branch] - push changes to remote (typicall called origin) and branch name (main branch is called master)
git merge branch - merge branch into current one
git diff [commit ref 1] [commit ref 2] - show difference between commits
git rebase - Rewrite time!  (becareful!)
```
## Config
The git config file is found in your project folder ./git/config

### Pull Requests
[How to make pull requests](https://docs.google.com/presentation/d/12XPsgBkarJLA6I1UJd7HK1izUpQfX2Lt2gQq91z9XNQ/edit?usp=sharing)