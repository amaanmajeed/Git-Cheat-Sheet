# Git Cheat Sheet

## Getting Started

### Installation
To install Git, visit the [official Git website](https://git-scm.com/downloads) and follow the instructions for your operating system.

## Setting up Git
To set up Git, you need to configure your name and email address. This is used to identify your commits:
```
$ git config --global user.name "Your Name"
$ git config --global user.email "you@example.com"
```


## Basic Git Commands:
```
git status
git add .
git commit -m "Message"
git push
```

## Create a new repository on the command line
Don't add readme. You will get these lines from your repository, which will be empty. Copy them and paste them into your terminal, making sure you are in the right Repository.
```
echo "# Name of Repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin <Link to the repo>
git push -u origin main
```


## Push an existing repository from the command line
```
git remote add origin <Link of the repository>
git branch -M main
git push -u origin main
```