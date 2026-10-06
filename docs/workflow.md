# Git Workflow Documentation

## Project Overview
This project demonstrates Git best practices using branching, pull requests, tags, and documentation.

## Workflow Followed

1. Created a GitHub repository.
2. Initialized the local repository and pushed the code to GitHub.
3. Created a `dev` branch from `main`.
4. Created a `feature/add-documentation` branch from `dev`.
5. Added project documentation in the feature branch.
6. Committed and pushed changes to GitHub.
7. Created a Pull Request to merge `feature/add-documentation` into `dev`.
8. Merged `dev` into `main`.
9. Added a `.gitignore` file.
10. Created a Git tag `v1.0` for the first release.

## Branching Strategy

```text
main
 └── dev
      └── feature/add-documentation
```

## Tools Used

- Git
- GitHub
- VS Code

## Outcome

Successfully demonstrated Git branching, pull requests, version tagging, and repository documentation following DevOps best practices.