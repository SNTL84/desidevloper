# Publish as a standalone GitHub repository

Chosen repository name: `sntl84-garba-classes` (lowercase kebab-case).

This starter is currently stored in the `desidevloper` project as a separate folder because the connected GitHub action cannot create a new repository.

## Create the dedicated repository
1. Open https://github.com/new while logged in as `SNTL84`.
2. Repository name: `sntl84-garba-classes`.
3. Description: `Garba and Dandiya learning resources and class collaboration hub`.
4. Choose Public or Private. Do not initialize another README.
5. Copy this directory's contents to a new local folder called `sntl84-garba-classes` and run:

```bash
git init
git add .
git commit -m "chore: initialize SNTL84 Garba classes hub"
git branch -M main
git remote add origin https://github.com/SNTL84/sntl84-garba-classes.git
git push -u origin main
```

## GitHub Pages
After pushing, open repository **Settings → Pages**, choose deployment from `main` and `/ (root)`, then save. The static landing page needs no build step.
