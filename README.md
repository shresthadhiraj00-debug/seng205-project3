# SENG205 Project 3

This repository contains the source code, documentation, and prototypes for the SENG205 project.

## Branching Workflow

We follow a **Git Feature Branch Workflow** to manage version control:

- **main**  
  - Production-ready / stable branch.  
  - Only updated from `develop` after testing and review.  

- **develop**  
  - Integration branch where all feature branches are merged.  
  - Serves as a staging area before changes go to `main`.  

- **feature/* (e.g., feature/login, feature/dashboard)**  
  - Short-lived branches created from `develop`.  
  - Used for specific tasks or features.  
  - Merged back into `develop` via Pull Requests.  
  - Deleted after merge to keep the repository clean.  

## Commit Convention

We use **Conventional Commits** to keep history readable:  

- `feat:` → a new feature  
- `fix:` → a bug fix  
- `docs:` → documentation changes  
- `chore:` → setup or maintenance tasks  

## Pull Request Workflow

1. Create a feature branch from `develop`.  
2. Commit changes with clear messages.  
3. Push to GitHub and open a Pull Request (PR).  
4. Review and merge into `develop`.  
5. After testing, merge `develop` into `main`.  
6. Delete the feature branch after merge.  
docs: add branching workflow details to README
