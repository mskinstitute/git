# Git & GitHub Course Notes

## Introduction to Git & GitHub

Git is a distributed version control system that helps developers track changes in their code efficiently. GitHub is a cloud-based platform that hosts Git repositories and enables collaboration among developers.

---

## Why Learn Git & GitHub?

- Track and manage code changes
- Collaborate with teams efficiently
- Maintain multiple versions of a project
- Work on open-source projects
- Automate deployments with CI/CD

---

## Installation & Setup

### Install Git

1. Download from [git-scm.com](https://git-scm.com/)
2. Install with default settings
3. Verify installation:
   ```sh
   git --version
   ```

### Configure Git

```sh
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

---

## Basic Git Commands

### Initializing a Repository

```sh
git init
```

### Cloning a Repository

```sh
git clone <repository_url>
```

### Checking Status

```sh
git status
```

### Staging Changes

```sh
git add <file>
```

### Committing Changes

```sh
git commit -m "Your commit message"
```

### Viewing Commit History

```sh
git log
```

### Checking Differences

```sh
git diff
```

---

## Working with Branches

### Creating a New Branch

```sh
git branch <branch_name>
```

### Switching Branches

```sh
git checkout <branch_name>
```

### Merging Branches

```sh
git merge <branch_name>
```

### Deleting a Branch

```sh
git branch -d <branch_name>
```

---

## Working with Remote Repositories

### Connecting a Remote Repository

```sh
git remote add origin <repository_url>
```

### Pushing Changes

```sh
git push origin <branch_name>
```

### Pulling Changes

```sh
git pull origin <branch_name>
```

### Fetching Remote Changes

```sh
git fetch
```

---

## Resolving Merge Conflicts

1. Identify conflicting files using `git status`
2. Open the files and manually resolve conflicts
3. Mark the conflicts as resolved:
   ```sh
   git add <file>
   ```
4. Commit the resolved changes:
   ```sh
   git commit -m "Resolved merge conflict"
   ```

---

## GitHub Essentials

### Creating a Repository on GitHub

1. Sign in to [GitHub](https://github.com/)
2. Click on `New Repository`
3. Enter repository details and create

### Connecting Local Repository to GitHub

```sh
git remote add origin <github_repo_url>
git push -u origin main
```

### Forking a Repository

1. Open the repository on GitHub
2. Click on `Fork`

### Creating a Pull Request

1. Navigate to your forked repository
2. Make changes and push to a new branch
3. Click on `Pull Request` and describe changes
4. Submit for review

---

## Git Ignore & Best Practices

### Creating a `.gitignore` File

```sh
touch .gitignore
```

Add files to ignore, e.g.,:

```
node_modules/
.env
*.log
```

### Best Practices

- Use meaningful commit messages
- Work in branches and merge frequently
-
- Pull before pushing changes
- Use `.gitignore` to avoid unnecessary files
- Keep repositories clean and organized

---

## Advanced Git

### Stashing Changes

```sh
git stash
```

### Retrieving Stashed Changes

```sh
git stash pop
```

### Rebasing a Branch

```sh
git rebase <branch_name>
```

### Undoing Commits

```sh
git reset --soft HEAD~1  # Undo last commit but keep changes
git reset --hard HEAD~1  # Undo last commit and discard changes
```

---

## Conclusion

Mastering Git & GitHub enhances productivity and collaboration in software development. Practice regularly and contribute to open-source projects to improve your skills.

---

**MSK Institute - Empowering Coders with Technology**

