## 🚀Essential Git Commands for Cloud & Data Engineering

---

### 1) 📁**Create/Clone Project**

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository in the current folder. |
| `git clone <repository_url>` | Copy a remote repository to your local machine. |

---

### 2) 🧳**Basic Snapshotting**

| Command | Description |
|---------|-------------|
| `git status` | Show the status of your working directory and staged changes. |
| `git add <filename>` | Stage a file for commit (use `git add .` to stage all changes). |
| `git commit -m "message"` | Commit staged changes with a clear message (e.g., "Update data pipeline DAG"). |
| `git restore <filename>` | Discard changes in your working directory for a specific file. |
| `git restore --staged <filename>` | Unstage a file without discarding changes. |

---

### 3) 🌐**Branching and Merging**

| Command | Description |
|---------|-------------|
| `git branch` | List all local branches. |
| `git branch <branch_name>` | Create a new branch. |
| `git branch -d <branch_name>` | Delete a local branch. |
| `git checkout <branch_name>` | Switch to a specific branch. |
| `git checkout -b <new-branch>` | Create and switch to a new branch in one command. |
| `git switch <branch_name>` | Modern alternative to checkout for switching branches. |
| `git merge <branch_name>` | Merge changes from another branch into your current branch. |
| `git merge --no-ff <branch_name>` | Merge with a merge commit (preserves branch history). |
| `git rebase <branch>` | Reapply commits from your current branch onto another branch (creates linear history). |
| `git cherry-pick <commit_hash>` | Apply a specific commit from one branch to another (useful for selective merges). |

---

### 4) 🔄**Sharing & Update Project**

| Command | Description |
|---------|-------------|
| `git remote -v` | Show remote server(s) associated with the repo. |
| `git remote add <name> <url>` | Add a new remote repository. |
| `git fetch` | Fetch updates from the remote repository (does not merge). |
| `git pull` | Fetch and merge changes from the remote branch. |
| `git pull --rebase` | Fetch and rebase instead of merge (creates cleaner history). |
| `git push` | Upload your local commits to the remote repository. |
| `git push -u origin <branch_name>` | Push a new branch to remote and set upstream tracking. |
| `git push --force` | Force push local commits (use with caution in shared repos). |
| `git push --tags` | Push all tags to the remote repository. |

---

### 5) ⚡**Inspection & Completion**

| Command | Description |
|---------|-------------|
| `git log` | Show commit history with messages and authors. |
| `git log --oneline` | Show compact commit history (one line per commit). |
| `git log --graph --all --decorate` | Show branching history visually. |
| `git diff` | Show differences between working directory and staged changes. |
| `git diff <branch1> <branch2>` | Show differences between two branches. |
| `git diff --cached` | Show differences between staged changes and last commit. |
| `git show <commit_hash>` | Display details of a specific commit. |
| `git blame <filename>` | Show who made changes to each line of a file (audit trail). |
| `git tag <tag_name>` | Create a tag for marking release versions or milestones. |
| `git tag -l` | List all tags in the repository. |
| `git reset --hard <commit>` | Reset working directory to a previous commit (use with caution). |
| `git revert <commit_hash>` | Create a new commit that undoes changes from a previous commit. |
| `git reflog` | Show a log of all HEAD references (helpful for recovering lost commits). |
| `git clean -fd` | Remove all untracked files and directories. |

---

### 6) 📊**Stashing & Temporary Changes**

| Command | Description |
|---------|-------------|
| `git stash` | Temporarily save uncommitted changes without committing them (useful when switching branches). |
| `git stash pop` | Restore stashed changes back to your working directory. |
| `git stash list` | Show all stashed changesets. |
| `git stash drop` | Delete a specific stashed changeset. |

---

### 7) 🔧**Configuration & Setup**

| Command | Description |
|---------|-------------|
| `git config --global user.name "name"` | Set your global Git username (one-time setup). |
| `git config --global user.email "email"` | Set your global Git email (one-time setup). |
| `git config --list` | Display all Git configuration settings. |

---

### 👤Author
Created by: AnaghaParkhi
Passionate about Data Engineering, Cloud, and Analytics
## License
MIT
