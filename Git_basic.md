## Basic Git Commands Reference

A quick guide to the most commonly used Git commands.

## What is Git?

- Git is a distributed version control system used to track changes in files and projects.
- Git allows you to save versions of your project using commits.
- GitHub is a platform used to host Git repositories and collaborate with others.

## Getting Started

- `git init` : Initialize a new local Git repository.
- `git clone <url>` : Download a project and its entire version history from a remote repository.
- `git status` : Shows the current state of the working directory and staging area.

## Connecting the User Account and Repo

- `git config --global user.name "Your Name"` : Sets the default name used for commits.
- `git config --global user.email "you@example.com"` : Sets the default email used for commits.
- `git config --list` : Displays the current Git configuration.
- `git branch -M main` : Renames the current branch to main.
- `git remote add origin <YOUR_REPO_URL_HERE>`: Connects the local repository to a remote repository.
- `git remote -v` : Lists the configured remote repositories.

## Staging & Committing

- `git add <file>` : Stages a specific file for the next commit.
- `git add .` : Stages all changes in the current directory.
- `git commit -m "<message>"` : Records the staged changes in the repository history.
- `git log` : Lists the commit history.
- `git log --oneline` : Displays the commit history in a compact format.

## Branching & Merging

- `git branch` : Lists all local branches in the current repository.
- `git branch <branch-name>` : Creates a new branch.
- `git switch <branch-name>` : Switches to the specified branch.
- `git switch -c <branch-name>` : Creates a new branch and switches to it.
- `git checkout <branch-name>` : Switches to the specified branch.
- `git checkout -b <branch-name>` : Creates a new branch and switches to it.
- `git merge <branch-name>` : Combines the specified branch's history into the current branch.

Remote Repositories

git remote -v: Lists all current configured remote repositories.

git remote add origin <url>: Adds a remote repository named origin.

git push <remote> <branch>: Uploads local commits to a remote repository.

git push -u origin main: Pushes the main branch and sets the upstream branch.

git pull <remote> <branch>: Fetches and merges changes from the remote repository.

git fetch <remote>: Downloads changes from a remote repository without merging them.

Inspection & History

git status: Lists new, modified, staged, and untracked files.

git diff: Shows changes that have not yet been staged.

git show <commit>: Displays the details and changes of a specific commit.

git log: Lists the version history for the current branch.

git log --oneline: Shows a short version of the commit history.

Undoing Changes

git reset <file>: Unstages the file while preserving its changes.

git revert <commit>: Creates a new commit that undoes the changes from a previous commit.

Getting Help

git help: Opens Git's general help documentation.

git <command> --help: Displays help and documentation for a specific Git command.

Basic Git Workflow

git init: Initialize the repository.

git status: Check the current repository status.

git add .: Stage the changes.

git commit -m "<message>": Commit the changes.

git remote add origin <YOUR_REPO_URL>: Connect the local repository to a remote repository.

git branch -M main: Set the main branch.

git push -u origin main: Push the project to the remote repository.

git pull origin main: Get the latest changes from the remote repository.
