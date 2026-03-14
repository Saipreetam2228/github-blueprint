# GitHub Secret Scanning

GitHub Secret Scanning is a security feature that detects sensitive information accidentally committed to a repository.

Secrets include credentials such as API keys, tokens, and passwords.

---

## Why Secret Scanning is Important

Accidentally exposing secrets in a repository can lead to serious security risks such as:

- unauthorized system access
- data breaches
- service misuse

Secret scanning helps detect these risks quickly.

---

## How Secret Scanning Works

GitHub automatically scans repository content for known secret patterns.

If a secret is detected, GitHub generates a security alert.

Developers can then remove or rotate the exposed credential.

---

## Examples of Secrets

Common secrets detected include:

```
API keys
access tokens
database passwords
private keys
authentication tokens
```

---

## Security Alerts

When a secret is detected:

1. GitHub generates a security alert.
2. The developer is notified.
3. The exposed secret should be revoked immediately.

---

## Benefits

Secret scanning helps developers:

- prevent accidental credential leaks
- improve repository security
- protect external services and APIs

---

## Next Topic

Next we will explore **GitHub Insights and repository analytics**.
