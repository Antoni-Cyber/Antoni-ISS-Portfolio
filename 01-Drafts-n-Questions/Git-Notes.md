# Git Command Cheat Sheet

| Command | Option/Usage | Description |
| :--- | :--- | :--- |
| **git init** | | Initializes a new local Git repository |
| **git clone** | `[url]` | Clones a repository from GitHub to your machine |
| **git config** | `--global user.name "Name"` | Sets your name for commit signatures |
| **git config** | `--global user.email "email"` | Sets your email for GitHub contributions |
| **git status** | | Lists all new or modified files to be staged |
| **git add** | `.` | Stages all changes in the current directory |
| **git add** | `[file]` | Stages a specific file for the next commit |
| **git commit** | `-m "message"` | Records a permanent snapshot of staged changes |
| **git commit** | `--amend** | Modifies the most recent commit message or content |
| **git push** | `-u origin [branch]` | Uploads local commits to the remote repository |
| **git pull** | | Fetches and merges changes from the remote to local |
| **git fetch** | | Downloads objects/refs from remote without merging |
| **git log** | `--oneline` | Shows a high-level, condensed commit history |
| **git log** | `-p` | Shows the full history with actual text differences |
| **git diff** | | Shows unstaged changes in your working directory |
| **git diff** | `--staged` | Shows changes that are staged but not yet committed |
| **git branch** | | Lists all local branches in the current repository |
| **git branch** | `-d [name]` | Deletes a specified branch (if already merged) |
| **git checkout** | `-b [name]` | Creates a new branch and switches to it |
| **git checkout** | `[name]` | Switches to an existing branch |
| **git checkout** | `-- [file]` | Discards local changes and reverts file to last save |
| **git merge** | `[branch]` | Merges the specified branch into the current branch |
| **git remote** | `-v` | Lists all remote connections and their URLs |
| **git remote** | `set-url origin [url]` | Changes the URL of the remote repository |
| **git rm** | `--cached [file]` | Removes file from Git tracking but keeps local file |
| **git mv** | `[old] [new]` | Renames/moves a file and stages the change |
| **git stash** | | Temporarily stores all modified tracked files |
| **git stash pop** | | Restores the most recently stashed files |
| **git reset** | `HEAD~1` | Undoes the last commit while keeping the file changes |
| **git reset** | `--hard HEAD` | **DANGER**: Wipes all unsaved changes and reverts to last commit |