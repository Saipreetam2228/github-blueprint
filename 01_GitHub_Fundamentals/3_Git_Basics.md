# Git Basics

Git is a distributed version control system used to track changes in files and collaborate on software projects.

Understanding basic Git commands is essential for working with GitHub.

---

## 1. git init

Initializes a new Git repository in a project.

Example:

```
git init
```

This creates a `.git` folder that allows Git to track changes.

---

## 2. git clone

Clones an existing repository from GitHub to your computer.

Example:

```
git clone https://github.com/username/repository-name.git
```

This downloads the entire project to your local machine.

---

## 3. git add

Adds files to the staging area before committing.

Example:

```
git add filename
```

To add all files:

```
git add .
```

---

## 4. git commit

Saves the changes with a message.

Example:

```
git commit -m "Added new feature"
```

A commit records the changes in the project history.

---

## 5. git push

Uploads your commits from your local repository to GitHub.

Example:

```
git push origin main
```

---

## 6. git pull

Downloads the latest changes from GitHub.

Example:

```
git pull origin main
```

---

## Basic Git Workflow

Typical workflow when working with Git:

1. Clone the repository
2. Make changes to files
3. Add changes using git add
4. Commit changes using git commit
5. Push changes to GitHub

---

## Next Topics

After learning Git basics, the next important topic is:

- Repositories
- Branching
- Pull Requests
