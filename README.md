# 🚀 Git & GitHub Learning Journey

This repository contains my **notes, commands, practice exercises, and learning progress** while exploring Git and GitHub as part of my **DevOps learning journey**.

The goal of this repository is to document my practical understanding of **version control, Git commands, GitHub collaboration, branching, and DevOps workflows**.

---

# 📚 Topics I Have Learned

## 1. Version Control System

A **Version Control System (VCS)** is used to manage and track changes made to files and source code.

### Why Version Control?

Version control helps with:

* Tracking code changes
* Maintaining different versions of code
* Collaborating with developers
* Recovering previous versions
* Managing projects safely
* Maintaining project history

---

# 2. Git

**Git** is a distributed version control system used to track changes in source code.

Git allows developers to:

* Track changes
* Create commits
* Manage branches
* Compare changes
* Restore previous versions
* Work with remote repositories
* Collaborate with other developers

---

# 3. Git Architecture

The basic Git workflow consists of four major areas:

```text
Working Directory
       ↓
Staging Area
       ↓
Local Repository
       ↓
Remote Repository
       ↓
GitHub
```

### Working Directory

The location where files are created and modified.

### Staging Area

The area where changes are prepared before committing.

### Local Repository

The Git repository stored on the local machine.

### Remote Repository

A repository stored on a remote server such as GitHub.

---

# 4. Basic Git Workflow

A basic Git workflow looks like this:

```text
Create / Modify Files
        ↓
    git status
        ↓
     git add
        ↓
    Staging Area
        ↓
    git commit
        ↓
 Local Repository
        ↓
     git push
        ↓
      GitHub
```

---

# 5. Important Git Commands

## Repository Commands

```bash
git init
git status
git clone <repository-url>
```

## File Tracking Commands

```bash
git add filename
git add .
```

## Commit Commands

```bash
git commit -m "commit message"
git commit --amend
```

## History Commands

```bash
git log
git log --oneline
git show
git diff
git blame
git shortlog
```

## Remote Repository Commands

```bash
git remote -v
git remote add origin <repository-url>
git push
git pull
git fetch
```

## Branch Commands

```bash
git branch
git branch feature
git switch feature
git merge feature
```

---

# 6. GitHub

**GitHub** is a platform used to host Git repositories and collaborate with developers.

I learned how to:

* Create GitHub repositories
* Connect local Git repositories with GitHub
* Push code to GitHub
* Pull changes from GitHub
* Clone repositories
* Manage remote repositories
* Work with branches
* Create Pull Requests
* Fork repositories
* Collaborate with other developers

---

# 7. GitHub Fork

A **Fork** creates a copy of another user's GitHub repository under my own GitHub account.

A fork is useful when contributing to a repository that I do not directly own.

### Fork Workflow

```text
Original Repository
        ↓
       Fork
        ↓
My GitHub Repository
        ↓
      Clone
        ↓
Local Repository
        ↓
      Changes
        ↓
      Commit
        ↓
       Push
        ↓
   Pull Request
```

---

# 8. Fork vs Clone

| Fork                                        | Clone                                |
| ------------------------------------------- | ------------------------------------ |
| Creates a repository copy on GitHub         | Creates a local copy                 |
| GitHub → GitHub                             | GitHub → Local Machine               |
| Used for contributing to another repository | Used to work on a repository locally |
| Creates a new repository under your account | Creates files on your local system   |

### Simple Difference

```text
Fork
GitHub Repository
       ↓
Another GitHub Account


Clone
GitHub Repository
       ↓
Local Machine
```

---

# 9. Pull Request

A **Pull Request (PR)** is used to propose changes to another repository or branch.

Typical workflow:

```text
Create / Fork Repository
        ↓
      Clone
        ↓
 Create Feature Branch
        ↓
   Make Changes
        ↓
     git add
        ↓
    git commit
        ↓
     git push
        ↓
 Pull Request
        ↓
    Code Review
        ↓
      Merge
```

---

# 10. Git Collaboration Workflow

The collaboration workflow I practiced is:

```text
Fork
 ↓
Clone
 ↓
Create Branch
 ↓
Make Changes
 ↓
git add
 ↓
git commit
 ↓
git push
 ↓
Pull Request
 ↓
Code Review
 ↓
Merge
```

This workflow allows developers to contribute changes while keeping the original repository protected.

---

# 11. Git and GitHub in DevOps

Git and GitHub are important foundations for DevOps because they can be integrated with CI/CD tools.

A typical DevOps workflow can look like:

```text
Developer
    ↓
Git
    ↓
GitHub
    ↓
Pull Request
    ↓
CI/CD Pipeline
    ↓
Build
    ↓
Test
    ↓
Artifact
    ↓
Deployment
```

Tools such as **Jenkins** and **GitHub Actions** can monitor repositories and automate build, test, and deployment processes.

---

# 12. Key Concepts Learned

Through my Git and GitHub practice, I learned:

```text
Version Control
      ↓
Git
      ↓
Git Repository
      ↓
Working Directory
      ↓
Staging Area
      ↓
Commits
      ↓
Branches
      ↓
Merge
      ↓
Remote Repository
      ↓
GitHub
      ↓
Fork
      ↓
Pull Request
      ↓
Collaboration
      ↓
CI/CD
```

---

# 🎯 Learning Outcome

My Git and GitHub practice helped me understand how source code can be:

* Version controlled
* Tracked through commits
* Organized using branches
* Stored remotely
* Shared through GitHub
* Collaborated on using Pull Requests
* Integrated into DevOps CI/CD pipelines

---

# 🚀 My DevOps Learning Journey

This repository represents my hands-on learning progress with **Git and GitHub**.

I am continuing to build my DevOps knowledge by practicing tools and technologies such as:

```text
Git
 ↓
GitHub
 ↓
Maven
 ↓
Jenkins
 ↓
CI/CD
 ↓
AWS
 ↓
Docker
 ↓
Terraform
 ↓
Kubernetes
```

**Learn → Practice → Build → Document → Improve 🚀**
