# Git commands I used

Quick notes so I don't have to look these up every time.

| Command | What it does |
| --- | --- |
| `git clone <url>` | Copies a repo from GitHub to my computer |
| `git status` | Shows which files changed and what is staged |
| `git branch` | Lists branches; the current one has a `*` |
| `git checkout -b <name>` | Creates a new branch and switches to it |
| `git add <file>` | Stages a file for the next commit |
| `git commit -m "message"` | Saves the staged changes with a message |
| `git push -u origin <branch>` | Uploads the branch to GitHub |
| `git pull` | Downloads and merges the latest changes from GitHub |

## Workflow in short

1. Clone the repo
2. Make a branch for the task
3. Change files, then `git add` and `git commit`
4. Push the branch
5. Open a Pull Request into `main`
6. Merge it, then `git pull` on `main` to sync

## Git vs GitHub

Git is the tool that tracks changes on my computer. GitHub is the website that hosts repos online and adds things like Pull Requests on top of Git.
