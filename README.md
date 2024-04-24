# Git Cheat Sheet

## Introduction to Git
**Git** is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

## Initializing

- `git init`: initializes a new Git repository. Converts the current directory into a Git working directory.
- `git clone [url]`: clones a repository into a new directory. Downloads an existing Git repository from another server.

## Branching

- `git branch`: lists all of the branches in your repo, showing the current branch with an asterisk.
- `git branch new-branch`: creates a new branch called **new-branch**. It does not check out the new branch.
- `git checkout another-branch`: Switches to the branch **another-branch**, updating the working directory to match.
- `git checkout -b new-branch`: creates and checks out a new branch called **new-branch**.
- `git branch -d branch-name`: deletes the branch named **branch-name**.

## Staging

- `git status`: shows the status of changes as untracked, modified, or staged.
- `git add [file]`: adds a file to the staging area. Makes it included in the next commit.
- `git reset [file]`: unstages a file while retaining the changes in the working directory.

## Committing

- `git commit -m "Commit message"`: commits the staged files with a message describing the change.
- `git commit -am "Commit message"`: combines adding files to the staging area and committing them in one step.
- `git commit --amend -m "New commit message"`: replaces the last commit with the new commit and message.
- `git log`: lists commits history.

## Collaborating and Sharing

- `git push origin main`: pushes your local commits to the main branch of the remote repository.
- `git pull`: fetches the latest changes from the remote repository and merges them into the current branch.
- `git merge upstream/main`: merges changes from the main branch of the upstream repository into your current branch.

## Showing Changes

- `git diff --staged`: shows file differences that are staged to be committed.
- `git diff a-branch..b-branch`: shows the differences between two branches.
