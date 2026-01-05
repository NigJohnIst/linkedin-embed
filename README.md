LinkedIn Embed
===============

This repository contains a single page with an embedded LinkedIn post.

Files
- index.html: contains the embedded LinkedIn iframe.

How to publish to GitHub

1. Initialize a git repository, commit, and create a GitHub repo (choose either method):

Using the GitHub CLI (`gh`):

```bash
git init
git add .
git commit -m "Add LinkedIn embed"
# Replace <owner>/<repo> with your GitHub username and repo name
gh repo create <owner>/<repo> --public --source=. --remote=origin --push
```

Manual remote setup:

```bash
git init
git add .
git commit -m "Add LinkedIn embed"
# Create a repo on github.com, then add the remote and push
git remote add origin https://github.com/<owner>/<repo>.git
git branch -M main
git push -u origin main
```

Notes
- Replace `<owner>/<repo>` with your GitHub username and desired repo name.
- If you want a different default branch name, adjust the `git branch -M` command accordingly.
