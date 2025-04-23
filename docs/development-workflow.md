# Development Workflow

Welcome to the 404 Tracker project! This guide explains how developers contribute — including coding standards, Git practices, and our CI/CD workflow.

---

##  Branching Strategy

We use a simple 3-branch system that maps to our deployment environments:

| Branch     | Purpose             |
|------------|---------------------|
| `main`     | Production-ready code |
| `staging`  | Pre-prod testing     |
| `dev`      | Active development   |

 Use feature branches off `dev`, like:
```bash
git checkout -b feat/add-sentry-logging
