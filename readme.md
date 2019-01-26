# Git & CLI workshop

[Slides](https://docs.google.com/presentation/d/1784rb52eZTSQqkX7A3v-d-ZyU7dER1QbGcoU76yrG8A/edit#slide=id.p)

## Goals: Learn about...

- Command line basic commands
- How to create a git repository and how it works
- How to use GitHub and GitHub flow

## AGENDA

- Tools for make software
- Command Line
- Tooling for command line
- Git: Version Control System
- Git Basics
- Git Usages
- GitHub
- GitHub Workflow
- Why you should use git

- Practice 1 Using the command line
- Practice 2 Creating a new git repository
- Practice 3 Making commits
- Practice 4 Exploring repositories
- Practice 5 Creating a repository in GitHub
- Practice 6 GitHub flow

### Tools for make software
- Text Editor
- Version Control System
- Command Line

### Command Line
- SO UNIX Systems
- Basic commands

### Practice 1:
- Open the terminal and print your current folder
- Go to your desktop and create a folder named "workshop"
- See this folder in your files application
- Create a file name "readme.md" in this folder

### Tooling for command line
- BASH
- Zsh
- FISH Shell
- Tmux
- Htop

[Chocolatey](https://chocolatey.org/)
[Brew](https://brew.sh/index_es)

### Git: Version Control System
- VCS history
- Git history
- Projects analized by git
- Open Source movement
- Why you should use git?

[Git](https://git-scm.com/)
[Download Git](https://git-scm.com/downloads)
[Free Git Book](https://git-scm.com/book/en/v2)
[Windows: Installing Git](https://hackernoon.com/install-git-on-windows-9acf2a1944f0)
[Git Bash](https://gitforwindows.org/)

For Linux users
> sudo apt-get install git

For MacOS users
> brew install git

For Windows users:
- Download the installer
- Start the installer
- Install **Git Bash** and **Git GUI**
- Select **Use Git from Git Bash only** / **Checkout windows-style** / **Use Min TTY**
- Launch **Git Batch**
*Too much for use git in windows!!! 😥*

### Practice 2:
- In your terminal go to the previous folder created
- Create a git repository
- See the git status
- Add the file "readme.md"
- Make a commit
- See the log

### Git Basics
- Create a new repository
- Git Areas and DAG
- Add a file
- Commit changes
- See the log
- Git monitoring

### Practice 3:
- Add a new file in the folder
- Add this change in the repository and see the log
- Make at least 3 commits

[Git Practice Reference](http://carlogilmar.me/post/git-resume/)

### Practice 4:
- Add something and discard changes
- Go to a previous commit
- Return to the last commit
- See the commit stats

### Git Usages
- See changes and discard
- Go to previous commits
- See file history
- See an specific commit
- Log stats
- Local Repository
- Remote Repository
- Clone a repository

### Practice 4:
- Clone the follow repository: https://github.com/carlogilmar/Learning_Manager.git
- See the log
- See the file history
- See an specific commit
- Go to a previous commit and go to the last commit

### GitHub:
- Create a new repository in GitHub
- Copy the URL with https
- Add this url as remote repository in the folder
- Push your changes
- See your changes in GitHub

### Practice 5:
- Create a new repository in GitHub
- Add a new file "index.html"
- Add html content and commit changes
- See this changes in GitHub
- Clone this repository in your local machine
- Modify the file in your local machine
- Commit changes
- Push your changes
- See your new changes in GitHub

### GitHub Workflow
- Git Workflows
- Fork a repository
- Open a pull request
- Merge conflicts
- Manage conflicts in GitHub
- Merge a pull request

### Practice 6:
- Go to the next repository: https://github.com/carlogilmar/git-basics-workshop
- Fork the repository in your GitHub account
- Modify the file <add-file>
- Open a new pull request

### Why you should use git

### Practice 1

1. Open the terminal and print your current folder

For list the current folder for *nix users:
> pwd

For list the current folder for windows users:
> <put-the-command>

2. Go to your desktop and create a folder named "workshop"

For *nix users
> ls
> cd Desktop
> mkdir workshop

3. See this folder in your files application and go

For *nix users
> ls
> cd workshop

4. Create a file name "readme.md" in this folder

For *nix users
> touch readme.md

### Practice 2

1. In your terminal go to the previous folder created
2. Create a git repository
> "git init"

3. See the git status
> "git status"

4. Add the file "readme.md"
> "git add readme.md"

5. Make a commit
> git commit -m "This is my first commit"

6. See the log
> git log

### Practice 3

1. Add a new file in the folder
> touch other-file.txt

2. Add this change in the repository and see the log
> git status
> git add other-file.txt
> git commit -m "Adding a new file"
> git log

3. Make at least 3 commits

### Practice 4

1. Add something in *other-file.txt* and discard changes
> git diff other-file.txt
> git checkout -- other-file.txt

2. Go to a previous commit
> git log
> git checkout <commit-hash>

3. Return to the last commit
> git checkout master

4. See the commit stats
> git log --pretty=oneline

### Practice 5

1. Clone the follow repository <add-repository>
> git clone https://github.com/carlogilmar/git-basics-workshop.git

2. See the log
> git log

3. See the file history
> git blame readme.md

4. See an specific commit
> git show 9e4fc70a

5. Go to a previous commit and go to the last commit
> git checkout 9e4fc70a
> git checkout master

