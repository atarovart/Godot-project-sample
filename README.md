# Project Template

This repository contains a baseline directory structure for quickly bootstrapping new projects.

## Why are `.gitkeep` files here?

By default, Git does not track empty directories. To preserve the folder hierarchy in the repository, a placeholder `.gitkeep` file is placed inside each empty directory.

## How to remove all `.gitkeep` files after copying the template

Once you have copied or cloned this template for a new project, clean up the placeholder files using Bash.

1. Open your terminal (Bash / Git Bash) and navigate to the project root directory.
2. *(Optional)* Preview the list of files to be removed:
   ```bash
   find . -name ".gitkeep" -type f
   ```
3. Delete all `.gitkeep` files:
   ```bash
   find . -name ".gitkeep" -type f -delete
   ```

## Initializing a fresh repository

If you downloaded this template using `git clone`, it is recommended to unlink it from the original template repository and start a clean commit history:

```bash
rm -rf .git
git init
git add .
git commit -m "Initial commit from template"
```
