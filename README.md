# Git Zero to Hero 🚀

A complete hands-on guide to learning Git from beginner to advanced level.

This repository documents my journey of mastering Git through practical examples, real-world workflows, and best practices used by professional software engineers and DevOps teams.

---

# 📖 Table of Contents

- Introduction
- What is Git?
- Why Git?
- Installation
- Git Configuration
- Creating a Repository
- Git Workflow
- Branching
- Merging
- Rebasing
- Stashing
- Tags
- Remote Repositories
- GitHub Integration
- Conflict Resolution
- Git Best Practices
- Useful Commands
- Project Structure
- Learning Roadmap
- Resources
- Author

---

# 📌 Introduction

Git is the world's most popular distributed version control system.

It helps developers track changes, collaborate with teams, maintain code history, and safely experiment with new features.

Whether you're building small applications or managing enterprise software, Git is an essential skill for every software engineer and DevOps professional.

---

# 🚀 What is Git?

Git is a Distributed Version Control System (DVCS) created by Linus Torvalds in 2005.

Git allows developers to:

- Track code changes
- Collaborate efficiently
- Restore previous versions
- Manage multiple branches
- Resolve merge conflicts
- Work offline
- Integrate with CI/CD pipelines

---

# ✨ Why Git?

## Benefits

- Fast
- Distributed
- Reliable
- Secure
- Open Source
- Lightweight
- Industry Standard

---

# 💻 Installation

## Verify Installation

```bash
git --version
```

---

# ⚙ Git Configuration

Configure your identity:

```bash
git config --global user.name "Your Name"

git config --global user.email "your@email.com"
```

Verify configuration

```bash
git config --list
```

---

# 📁 Create a Repository

```bash
mkdir my-project

cd my-project

git init
```

---

# 📂 Git Workflow

Basic Git workflow:

```
Working Directory
        │
        ▼
git add
        │
        ▼
Staging Area
        │
        ▼
git commit
        │
        ▼
Local Repository
        │
        ▼
git push
        │
        ▼
GitHub Repository
```

---

# 🌿 Branching

Create a branch

```bash
git branch feature/login
```

Switch branch

```bash
git checkout feature/login
```

Create and switch

```bash
git checkout -b feature/login
```

---

# 🔀 Merging

Merge a branch

```bash
git checkout main

git merge feature/login
```

---

# 🔄 Rebasing

```bash
git checkout feature/login

git rebase main
```

---

# 📦 Stashing

Save changes temporarily

```bash
git stash
```

Restore changes

```bash
git stash pop
```

---

# 🏷 Tags

Create a tag

```bash
git tag v1.0
```

Push tags

```bash
git push origin --tags
```

---

# 🌍 Working with GitHub

Clone repository

```bash
git clone https://github.com/username/project.git
```

Connect local repository

```bash
git remote add origin https://github.com/username/project.git
```

Push

```bash
git push origin main
```

Pull

```bash
git pull origin main
```

Fetch

```bash
git fetch
```

---

# ⚠ Merge Conflict

Resolve conflicts by:

- Opening the conflicting files
- Choosing the correct changes
- Saving the file
- Adding it again

```bash
git add .

git commit
```

---

# 📚 Most Used Git Commands

```bash
git init

git clone

git status

git add .

git commit -m "message"

git push

git pull

git fetch

git log

git diff

git branch

git checkout

git merge

git rebase

git stash

git tag

git reset

git revert

git remote -v
```

---

# 📁 Example Project Structure

```
git-zero-to-hero/

│

├── README.md

├── images/

├── examples/

├── exercises/

├── cheatsheets/

└── resources/
```

---

# 🎯 Learning Roadmap

- Git Basics
- Repository Management
- Staging Area
- Commit History
- Branching
- Merge
- Rebase
- Tags
- GitHub
- Pull Requests
- Merge Conflicts
- Git Best Practices
- Git Workflows
- Git Hooks

---

# ⭐ Best Practices

- Write meaningful commit messages
- Commit frequently
- Pull before pushing
- Create feature branches
- Keep branches focused
- Review changes before committing
- Never commit secrets
- Use `.gitignore`
- Tag releases
- Keep commit history clean

---

# 📚 Useful Resources

- Git Official Documentation
- Pro Git Book
- GitHub Documentation
- Atlassian Git Tutorials

If you found this repository useful, don't forget to ⭐ star it.

Happy Coding! 🚀
