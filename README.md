Here's a formatted version of the provided content suitable for a GitHub `README.md` file:

```markdown
# Git Commands Cheat Sheet

A handy guide to commonly used Git commands.

**## Version Control**

## Check Git Version:
  ```bash
  git --version
  ```

## Configuration

- **Set User Name:**
  ```bash
  git config --global user.name "Talha"
  ```
- **Set User Email:**
  ```bash
  git config --global user.email talha@gmail.com
  ```
- **Check Configuration:**
  ```bash
  git config --list
  ```

## Repository Setup

- **Initialize a Repository:**
  ```bash
  git init
  ```
- **Check for Git Repository:**
  ```bash
  git ls -la
  ```

## Staging and Committing

- **Add Files to Staging:**
  ```bash
  git add . # Adds all files
  git add <filename> # Adds specific file
  ```
- **Commit Changes:**
  ```bash
  git commit -m "Type your message here"
  ```

## Branching

- **Check Current Branch:**
  ```bash
  git branch
  ```
- **Create New Branch:**
  ```bash
  git branch <newbranchname>
  ```
- **Switch to a Branch:**
  ```bash
  git checkout <branch name>
  ```

## Logs and History

- **See All Commits:**
  ```bash
  git log
  ```
- **See Last Two Commits with Differences:**
  ```bash
  git log -p -2
  ```
- **Summary of Changes:**
  ```bash
  git log --stat
  ```
- **Show Commits in One Line:**
  ```bash
  git log --pretty=oneline
  ```
- **Check When Specific Tag Was Used:**
  ```bash
  git log -S "h1"
  ```
- **Search Commits by Message:**
  ```bash
  git log --grep="message you want to check"
  ```

## Differences and Status

- **Check Differences Between Commits:**
  ```bash
  git diff
  ```
- **Check Status:**
  ```bash
  git status
  ```

## Viewing and Restoring Files

- **View a Specific Old File:**
  ```bash
  git show <commit ID>:<filename>
  ```
- **Restore Old Version of a File:**
  ```bash
  git checkout <commit ID> -- <filename>
  ```
- **Return to Last Code:**
  ```bash
  git checkout master -- *
  ```
- **Undo Changes Made by Mistake:**
  ```bash
  git restore .
  ```
- **Undo Staged Changes:**
  ```bash
  git restore --staged .
  ```
- **Reset to a Previous Commit:**
  ```bash
  git reset --hard HEAD^
  git reset --hard <commit ID>
  ```

## Pushing and Pulling

- **Push Code to GitHub:**
  ```bash
  git remote add origin <github repo URL>
  git branch -M main
  git push -u origin main
  ```
- **Pull from Remote to Local:**
  ```bash
  git pull
  ```
- **Clone a Remote Repository:**
  ```bash
  git clone <https github URL>
  ```
- **Check Remote Repository:**
  ```bash
  git remote -v
  ```

## Branching and Merging

- **Merge a Branch:**
  ```bash
  git merge <new branch name>
  ```

## Forking

- **Fork a Repository:**
  - Creates a copy of another user's repository, allowing you to contribute with a pull request.

## Git Ignore

- **Create `.gitignore`:**
  - Add secret files like `secret.html` or `password.json` to automatically ignore them.
- **Clean Untracked Files (without deletion):**
  ```bash
  git clean -n
  ```
- **Clean and Delete Untracked Files:**
  ```bash
  git clean -f
  ```

## Tags

- **Add a Tag to Current Commit:**
  ```bash
  git tag -a <name> -m "type name"
  ```
- **Check Commit Using Tag:**
  ```bash
  git show <tag name>
  ```
```

This version organizes your Git commands into sections for easier readability and understanding, making it suitable for a GitHub `README.md` file.
