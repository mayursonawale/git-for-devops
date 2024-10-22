
# Git Commands with Descriptions

## Basic Commands
- **`git init`**  
  Initializes a new Git repository in your project directory.
  
- **`git clone <repo-url>`**  
  Clones an existing repository from a remote (e.g., GitHub) to your local machine.

- **`git status`**  
  Displays the current status of the working directory and staging area.

- **`git add <filename>`**  
  Adds a specific file to the staging area. Use `git add .` to add all files.

- **`git commit -m "message"`**  
  Commits staged changes with a descriptive commit message.

- **`git push`**  
  Pushes committed changes to the remote repository.

- **`git pull`**  
  Fetches changes from the remote repository and merges them into your local branch.

- **`git remote add origin <repo-url>`**  
  Links your local repository to a remote repository (e.g., GitHub).

## Branching and Merging
- **`git branch`**  
  Lists all branches in your repository. Highlights the current branch.

- **`git branch <branch-name>`**  
  Creates a new branch.

- **`git checkout <branch-name>`**  
  Switches to the specified branch.

- **`git merge <branch-name>`**  
  Merges the specified branch into the current branch.

- **`git branch -d <branch-name>`**  
  Deletes a branch.

## Undoing Changes
- **`git reset <file>`**  
  Removes the specified file from the staging area.

- **`git reset --hard`**  
  Resets the working directory to the last commit, discarding all changes.

- **`git revert <commit-id>`**  
  Creates a new commit that undoes the changes from the specified commit.

- **`git stash`**  
  Temporarily saves changes in a "stash" to be applied later.

- **`git stash apply`**  
  Applies the most recently stashed changes.

## Viewing History
- **`git log`**  
  Shows the commit history for the current branch.

- **`git log --oneline`**  
  Displays the commit history in a concise format (one commit per line).

- **`git show <commit-id>`**  
  Displays detailed information about a specific commit.

## Collaboration
- **`git fetch`**  
  Downloads changes from the remote repository but does not merge them.

- **`git pull`**  
  Fetches and merges changes from the remote repository into your local branch.

- **`git push origin <branch>`**  
  Pushes a branch to the remote repository.

- **`git remote -v`**  
  Displays the remote repositories associated with the local repository.

## Tags
- **`git tag <tagname>`**  
  Creates a new tag pointing to the current commit.

- **`git push origin <tagname>`**  
  Pushes a tag to the remote repository.

## Git Configuration
- **`git config --global user.name "Your Name"`**  
  Sets the name you want to associate with your Git commits.

- **`git config --global user.email "your.email@example.com"`**  
  Sets the email you want to associate with your Git commits.

## Git Ignore
- **`.gitignore`**  
  A file specifying which files or directories Git should ignore. Add patterns for files that shouldn't be tracked.
