# DEPLOY - Coming Soon Repo (Public)

This file is for the public prelaunch repo:

- Repo name: `servicedesksim-coming-soon`
- Local folder: `coming-soon-package/`
- Target URL: `https://<username>.github.io/servicedesksim-coming-soon/`

## One-Time Setup

```powershell
cd C:\Users\<your-user>\ServiceDeskSimWebSite\coming-soon-package
git init
git add .
git commit -m "Initial coming soon site"
git branch -M main
git remote add origin https://github.com/<your-username>/servicedesksim-coming-soon.git
git push -u origin main
```

## Enable GitHub Pages

1. Open repo on GitHub.
2. Go to `Settings` -> `Pages`.
3. Set `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save.

## Update Deploy (Normal)

```powershell
cd C:\Users\<your-user>\ServiceDeskSimWebSite\coming-soon-package
git add .
git commit -m "Update coming soon page"
git push
```

## Quick Verification

1. Confirm page loads.
2. Confirm form loads and submits.
3. Confirm itch link is `https://reprodev.itch.io/servicedesksim`.
4. Confirm no links to hidden full-site pages.
