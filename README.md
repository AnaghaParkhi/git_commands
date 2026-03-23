| Category                             | Command                              | Description                                        |
|--------------------------------------|--------------------------------------|----------------------------------------------------|
| **Create/Clone Project**             | `git init <project>`                 | Initialize a new Git repository.                    |
|                                      | `git clone <repository>`             | Clone an existing repository.                        |
| **Basic Snapshotting**               | `git add <file>`                     | Stage changes to the specified file.                |
|                                      | `git commit -m "message"`          | Commit staged changes with a descriptive message.   |
|                                      | `git status`                         | Check the status of files in the working directory.  |
| **Branching and Merging**            | `git branch <branch>`                | Create a new branch.                                |
|                                      | `git checkout <branch>`              | Switch to the specified branch.                      |
|                                      | `git merge <branch>`                 | Merge the specified branch into the current branch.  |
| **Sharing & Update Project**        | `git push origin <branch>`           | Push changes to the remote repository.              |
|                                      | `git pull origin <branch>`           | Fetch and merge changes from the remote repository.  |
|                                      | `git fetch`                          | Fetch changes from the remote repository without merging.|
| **Inspection & Completion**          | `git log`                            | View the commit history.                             |
|                                      | `git diff`                           | Show changes between commits, branches, or files.   |
|                                      | `git show <commit>`                  | Display changes introduced by a specific commit.     |
| **Stashing & Temporary Changes**    | `git stash`                          | Temporarily save changes in a dirty working directory.|
|                                      | `git stash apply`                    | Apply stashed changes back to the working directory.  |
|                                      | `git stash drop`                     | Discard the most recent stash.                       |
| **Configuration & Setup**            | `git config --global user.name "Name"` | Set user name for all repositories.            |
|                                      | `git config --global user.email "email@example.com"` | Set user email for all repositories. |