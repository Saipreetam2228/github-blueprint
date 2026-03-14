# GitHub Actions

GitHub Actions is a powerful automation tool provided by GitHub.

It allows developers to automate workflows directly inside a repository.

---

## What is Automation

Automation means performing tasks automatically without manual intervention.

In software development, automation is used to:

- run tests
- build applications
- deploy code
- check code quality

---

## What GitHub Actions Can Do

GitHub Actions can automatically:

- run tests when code is pushed
- build projects
- deploy websites
- run scripts
- automate development workflows

---

## Workflow Concept

GitHub Actions works using **workflows**.

A workflow is a set of automated steps defined in a file.

These files are stored in:

```
.github/workflows/
```

---

## Example Workflow

Example automation:

```
Push code → Run tests → Build project → Deploy
```

---

## Workflow File Example

Example YAML workflow file:

```
name: Example Workflow

on: push

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v3
```

---

## Benefits of GitHub Actions

GitHub Actions helps developers:

- automate repetitive tasks
- improve development efficiency
- maintain code quality
- simplify deployments

---

## Next Topic

Next we will explore **documentation features like README and GitHub Wiki**.
