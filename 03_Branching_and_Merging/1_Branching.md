# Branching in Git

Branching is a feature in Git that allows developers to work on different parts of a project without affecting the main code.

Each branch represents an independent line of development.

---

## Why Branching is Important

Branching allows developers to:

- work on new features
- fix bugs
- experiment with changes
- collaborate safely

Without affecting the main project.

---

## Main Branch

Most repositories contain a default branch called:

```
main
```

This branch usually contains the **stable version of the project**.

---

## Creating a Branch

Developers create new branches to work on specific features.

Example:

```
git branch feature-login
```

This creates a branch named **feature-login**.

---

## Switching Branches

To switch to another branch:

```
git checkout feature-login
```

Or using the modern command:

```
git switch feature-login
```

---

## Viewing Branches

To see all branches:

```
git branch
```

---

## Example Workflow

A developer working on a login feature might do:

1. Create a branch

```
git branch feature-login
```

2. Switch to the branch

```
git checkout feature-login
```

3. Develop the feature

---

## Next Topic

Next we will learn about **Merging branches**.
