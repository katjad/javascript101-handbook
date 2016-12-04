# Version Control

In order to manage your own code and share code with others you need to use version control.

## Git
Git is the standard version control system for open source and professional projects.

You can view our projects on [Github/CodeHub](https://github.com/CodeHubOrg/)

Using git is easy once you know how!  You just need to know the basic concepts and commands to get going.

[Useful Git techniques + other resources
](https://github.com/CodeHubOrg/discussions/issues/12)

A great way to learn is by doing a workshop.  Open a terminal window and type the following:
```
npm install -g git-it
git-it
```

## Useful commands
```
git clone [url] - clone a git repo
git checkout [branch] - check out a branch
git checkout -b [branch] - make a new branch based on current branch
git add . - add all files
git add -u - add deleted files
git commit -am "[commit message]" - add and commit with message
git push [remote] [branch] - push changes to remote (typicall called origin) and branch name (main branch is called master)
```
## Config
The git config file is found in your project folder ./git/config

### Pull Requests
[How to make pull requests](https://docs.google.com/presentation/d/12XPsgBkarJLA6I1UJd7HK1izUpQfX2Lt2gQq91z9XNQ/edit?usp=sharing)