# Essential Git Commands for Cloud & Data Engineering

In today's data-driven world, Git has become an essential tool for version control in software development and data engineering. Here’s a quick guide to some of the most essential Git commands:

## Basic Commands

1. **git init**: Initializes a new Git repository.
2. **git clone <repository>**: Creates a copy of an existing repository.
3. **git add <file>**: Stages a file for commit. Use `git add .` to stage all files.
4. **git commit -m "<message>"**: Commits the staged changes with a message.
5. **git push <remote> <branch>**: Pushes your changes to a remote repository.

## Branching and Merging

1. **git branch**: Lists all branches in the repository.
2. **git branch <new-branch>**: Creates a new branch.
3. **git checkout <branch>**: Switches to the specified branch.
4. **git merge <branch>**: Merges the specified branch into the current branch.

## Viewing Changes

1. **git status**: Shows the status of changes as untracked, modified, or staged.
2. **git diff**: Shows changes between commits, commit and working tree, etc.
3. **git log**: Displays the commit history.

## Remote Repositories

1. **git remote -v**: View the remote repositories linked to your local repository.
2. **git fetch**: Fetches changes from the remote repository without merging.
3. **git pull**: Fetches and merges changes from the remote repository.

## Useful Options

1. **-a**: For `git commit`, it stages all tracked files automatically.
2. **--amend**: To amend the previous commit with new changes.
3. **--hard**: To reset your branch to a previous commit and discard local changes.

This guide provides a brief overview of the critical Git operations you’ll frequently use in Cloud & Data Engineering projects. Mastering these commands will enhance your productivity and efficiency in managing code and data workflows.
