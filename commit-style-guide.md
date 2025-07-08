Here’s your **Git Commit Style Guide** in Markdown format. You can copy this into a file named `commit-style-guide.md` (or similar) and share it with your team or keep it in your project repo.

---
```markdown
# 📝 Git Commit Style Guide

This guide follows the [Conventional Commits](https://www.conventionalcommits.org/) standard for writing clear, consistent, and meaningful commit messages.

---

## 📌 Commit Message Format

```

<type>(optional-scope): <short summary>

\[optional body]

\[optional footer: issues, breaking changes]

````

- Use the **imperative mood** (e.g., "fix", "add", "refactor" — not "fixed" or "adds")
- Keep the **summary line under 50 characters**
- Separate header from body with a **blank line**
- Wrap the body at **72 characters** if needed

---

## 🔠 Commit Types

| Type       | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| `feat`     | Introduces a new feature                                                    |
| `fix`      | Fixes a bug                                                                 |
| `docs`     | Documentation changes only                                                  |
| `style`    | Code style changes (formatting, spacing, etc.; no logic change)            |
| `refactor` | Refactors code without changing behavior                                    |
| `perf`     | Performance improvements                                                    |
| `test`     | Adds or updates tests                                                       |
| `build`    | Changes to build tools or dependencies (e.g., Webpack, Docker)             |
| `ci`       | Changes to CI/CD configuration (e.g., GitHub Actions, Travis)              |
| `chore`    | Maintenance tasks (e.g., bumping versions, minor cleanups)                 |
| `revert`   | Reverts a previous commit                                                   |

---

## ✅ Examples

```bash
feat(auth): add JWT authentication flow

fix(login): correct password validation error

docs: update installation instructions in README

style: reformat codebase using Prettier

refactor(api): extract request handler logic

perf(image-loader): reduce image load time by 40%

test(auth): add unit tests for login middleware

build: upgrade Webpack to version 5

ci(github): fix node version in GitHub Actions

chore: update dependencies to latest versions

revert: feat(auth): add JWT authentication flow
````

---
---

## 📚 Resources

* [Conventional Commits](https://www.conventionalcommits.org/)
* [Semantic Release](https://semantic-release.gitbook.io/semantic-release/)
* [Keep a Changelog](https://keepachangelog.com/)

```
