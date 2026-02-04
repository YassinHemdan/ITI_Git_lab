
# ITI Git Lab

This repository contains the Git lab for the ITI Intensive Code Camps (ICC). The exercises are designed to teach core Git and GitHub workflows through short, focused tasks you can complete locally.

## Lab Overview

- **Duration:** 30 min – 1 hour
- **Topics:** Git basics, branching, commits, merging, resolving conflicts, remote workflows, PRs
- **Goal:** Build confidence using Git for real-world collaboration and version control.

## Prerequisites

- A GitHub account
- Basic familiarity with the command line (PowerShell, Terminal)

## Quick Setup

1. Clone the repo:

	git clone <https://github.com/YassinHemdan/ITI_Git_lab.git>

2. Change into the project directory:

	cd "ITI_Git_lab"

3. Inspect files and start working.

## Exercises 1
1. Basic commit
    - Modify `index.html` by adding a new li with name one of team member.
    - Commit and push the branch.
2. Check commits
    - Use `git log` and `git diff` to review your commits.



    ##  Git Commands Used 
- `git clone <repo-url>` clone the repository to your local machine
- `cd "ITI_Git_lab"` change into the project directory
- `git status` check the status of your working directory
- `git add index.html` stage changes to index.html for commit
- `git commit -m "Added li with name <name>"` commit staged changes with a message
- `git push origin main` push the changes to the remote repository
- `git log` view the commit history


## Exercises 2

The lab contains several short exercises. For each task, create a dedicated branch, complete the work, commit often, and push to your fork or branch.

1. Initialize a new branch
	- Create a branch `with name <name-branch>`.
	- Add a new  `li with <name-branch>` with a short message.
	- Commit and push the branch.

2. Branching and merging
    - Merge branches locally and resolve merge conflicts.
    - Push the merged changes.


##  Git Commands Used 

- `git pull`  pull the latest changes from the remote repository
- `git checkout -b branch-name` create and switch to a new branch
- `git add .` stage all changes for commit
- `git commit -m "branch-name"` commit staged changes with a message
- `git push origin branch-name` push the branch to the remote repository
- `git checkout main` switch back to the main branch
- `git merge branch-name` merge the specified branch into the current branch
- `git push origin main` push the updated main branch to the remote repository


## Resources

- GitHub Docs: https://docs.github.com
