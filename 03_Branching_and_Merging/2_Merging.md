# Merging Branches in Git

Merging is the process of combining changes from one branch into another.

It is commonly used to integrate new features into the main project.

---

## Why Merging is Important

Merging allows developers to:

- combine completed features
- integrate bug fixes
- update the main project safely

---

## Example Scenario

Suppose a developer created a branch called:

```
feature-login
```

After finishing the feature, the changes need to be added to the **main branch**.

---

## Steps to Merge a Branch

### Step 1

Switch to the main branch.

```
git checkout main
```

---

### Step 2

Merge the feature branch.

```
git merge feature-login
```

This combines the changes into the main branch.

---

## Merge Conflicts

Sometimes Git cannot automatically merge changes.

This happens when:

- two developers edit the same file
- changes conflict with each other

Git will mark these as **merge conflicts**, which must be resolved manually.

---

## After Merging

Once merging is complete:

- the feature becomes part of the main project
- the branch can optionally be deleted

Example:

```
git branch -d feature-login
```

---

## Next Topic

Next we will learn about **Pull Requests**, one of the most powerful collaboration features on GitHub.
