# Collaboration Guide

## Initial upload

1. Unzip the starter; open the inner `fyp-3d-gaussian-splatting` folder in VS Code.
2. Create an empty private GitHub repository with that name. Do not initialize another README, license or .gitignore there because the starter already includes local files.
3. In the terminal opened in this folder, run the commands below, replacing YOUR_USERNAME.

```bash
git init
git add .
git commit -m "Initialize FYP research workspace"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/fyp-3d-gaussian-splatting.git
git push -u origin main
```

If Git requests author identity, configure your own GitHub-linked name/email (or GitHub noreply address) and retry the commit. Authenticate using GitHub's supported login flow; do not put credentials into files.

## Invite teammates

Repository Settings → Collaborators → Add people → choose their GitHub accounts. They must accept. You may invite a new member later. Share the Google Sheet separately with Editor access.

## Daily work

- Keep the master Google Sheet as the live literature review; export dated backups at milestones.
- For repository edits, update main, create a descriptive branch such as `fatima/paper-notes`, commit changes and push that branch.
- Open a pull request into main. Ask another member to review before merging.
- Pull merged changes before starting the next task. Avoid editing the same binary document simultaneously.
- Use GitHub Issues for tasks, with an owner, deadline and completion evidence.
- Use individual accounts and GitHub-linked commit emails so contributions can be attributed.
- Preserve submitted documents in their dated submission folders; record code commit/tag instead of duplicating code.
- Store meeting notes as `YYYY-MM-DD.md`: attendees, decisions, action owners and deadlines.

## Before making public

Agree with the team and supervisor on release scope. Check current files and Git history for private forms, secrets and restricted assets. Preserve third-party code licenses and paper citations. Add an appropriate license only after agreement.
