# GitHub Website Lab

This repository contains the files for Activities 1, 2, and 3. The websites use a cyberpunk neon theme.

## Activity 1

Open `activity-1/index.html` in a browser. It links to the About page and shared stylesheet.

## Activity 2: Troubleshooting

The teammate skipped staging `contact.html`. A file must be staged with `git add` before it is included in a commit. A push only sends commits to GitHub; it does not automatically include unstaged or uncommitted changes.

```bash
git add contact.html
git commit -m "Add contact page"
git push
```

If the file is already tracked and modified, `git add contact.html` stages its latest changes. If it is a new file, the same command stages it for the first time.

## Activity 3

The TechTreasure Blog pages and design brief are in `activity-3/`. The `feature-navbar` branch adds navigation to both pages.
