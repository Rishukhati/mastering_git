# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Overview

This appears to be a Git learning and tutorial repository named "mastering-git". The repository is currently empty and ready for Git learning exercises and examples.

## Common Development Commands

Since this is a Git learning repository, the primary commands will be Git-related:

```bash
# Initialize repository (if needed)
git init

# View repository status
git status

# View commit history
git log --oneline

# View detailed log with branches
git log --graph --oneline --all

# Create and switch to new branch
git checkout -b <branch-name>

# Stage files
git add <file>
git add .

# Commit changes
git commit -m "commit message"

# Push to remote
git push origin <branch-name>

# Merge branches
git merge <branch-name>

# View differences
git diff
git diff --staged
```

## Expected Repository Structure

As this is a Git tutorial repository, it will likely contain:

- Example files for Git operations (text files, code samples)
- Directories demonstrating branching and merging scenarios  
- Documentation and exercises for Git concepts
- Potentially scripts for setting up Git scenarios

## Git Learning Focus Areas

This repository is likely designed to cover:

- Basic Git workflow (add, commit, push, pull)
- Branching and merging strategies
- Conflict resolution
- Remote repository management
- Advanced Git features (rebase, cherry-pick, etc.)
- Git best practices and workflows

## Development Notes

- This is primarily a learning repository, so focus on clear commit messages and logical commit structure
- Each exercise or concept should be in its own branch or directory
- Maintain clean history for educational purposes
- Document any complex Git operations with explanations