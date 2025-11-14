# Git-Commands

## 1. Git Setup
Sets your name for all Git commits on your system.
```sh
git config --global user.name "Your Name"
```

Sets the email used in commit history.

```sh
git config --global user.email "you@example.com"
```

Shows all Git configuration values (name, email, editor, etc.).
```sh
git config --list
```


## 2. Create / Clone Repository 
Creates a new empty Git repository in the current folder.
```sh
git init
```

Downloads an existing repository from GitHub/GitLab/etc.
```sh
git clone <repo_url>
```

Clones into a specific folder name.
```sh
git clone <repo_url> <targate_folder>
```


## 3. Check Status
Shows current changes, untracked files, and branch info.
```sh
git status
```

## 4. Add files
Add a file to the staging area (ready to commit).
```sh
git add <file_name>
```

Add all modified and new files from current diractory
```sh
git add .
```

## 5 Commit Changes 
commit the repo change with commit message
```sh
git commmit -m "message"
```
commit and add
```sh
git commit -am "message"


## 6 View History and logs
show the detailed commit history 
```sh
git log
```
Shows short one-line history per commit.
```sh
git log --oneline
```



































