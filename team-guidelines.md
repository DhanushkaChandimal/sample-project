# Team Collaboration Guidelines

## Introduction

This document outlines our team collaboration practices for working on the project.
Following these guidelines helps keep the code organized, improves teamwork, and
ensures a clear project history.

---

## Branch Naming Conventions

Branches should follow this format:

```text
type/short-description
```

### Examples

```text
feature/user-authentication
bugfix/login-redirect-error
release/v1.2.0
```

### Branch Types

| Prefix | Purpose |
| --- | --- |
| `feature/` | New functionality or enhancements |
| `bugfix/` | Corrections to existing functionality |
| `release/` | Preparation for production deployment |

---

## Commit Message Best Practices

Commit messages explain what changed and why it changed.
They help teammates understand project history and make debugging and
collaboration easier.

### Structure of a Good Commit Message

- Summary line (50 characters or less)
- Use imperative mood (for example: `Add`, `Fix`, `Update`)
- Add a blank line after the summary
- Optional detailed body
- Explain why the change was made
- Mention important context or side effects if needed
- Keep lines around 72 characters for readability

### Example

```text
Add user authentication to login page

Implements JWT-based authentication to secure user sessions.
Replaces the previous session-based approach used earlier.
```

### Best Practices

- Be clear and specific
- Use present/imperative tense (`Add`, `Fix`, `Improve`)
- Explain why the change was made, not just how
- Keep each commit focused on one logical change
- Avoid vague messages like `update`, `fix bug`, or `changes`