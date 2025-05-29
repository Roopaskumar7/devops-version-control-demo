# DevOps Version Controlled Project

## Overview
This project demonstrates Git best practices for managing a DevOps project with:
- Proper branching strategy (main, dev, feature)
- Usage of pull requests to merge code
- Tags to mark releases
- A `.gitignore` file to exclude unnecessary files

## Branching Strategy
- `main`: Stable production-ready branch
- `dev`: Integration branch for features before release
- `feature/<feature-name>`: Branches created for new features

## Git Workflow
1. Create feature branch from `dev`.
2. Work and commit changes on feature branch.
3. Open pull request to `dev`.
4. After approval, merge feature branch into `dev`.
5. Periodically merge `dev` into `main` for releases.
6. Tag release versions on `main`.

## Tags
- v1.0: Initial stable release
- v1.1: Minor update

## .gitignore
Typical DevOps ignores like `.env`, logs, build files etc.

---

**All tasks are documented using markdown as required.**
