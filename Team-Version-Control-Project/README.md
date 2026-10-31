# Team Version Control Project

A small sample team project used to demonstrate Git and GitHub collaboration:
- a shared project structure
- module-specific branches
- commits and pull requests
- code review before merging
- merge conflict resolution

## Project modules
- `modules/module1.py` — greeting module
- `modules/module2.py` — status module
- `modules/module3.py` — summary module

## Suggested team workflow
1. Clone the repository.
2. Create a branch for your assigned module (for example, `feature/module1`).
3. Make changes and commit them on that branch.
4. Push the branch to GitHub.
5. Open a pull request targeting `main`.
6. Ask a teammate to review the changes.
7. Merge the pull request after approval.
8. Repeat for the remaining modules.

## Merge conflict practice
To practice conflict resolution, have two branches edit the same line in `conflict-practice.txt`.
Merge one branch first, then merge the other. Git will report a conflict.
Edit the file so both intended changes are preserved, then run:

```bash
git add conflict-practice.txt
git commit -m "Resolve merge conflict"
```

## Run the sample
From the project root:

```bash
python main.py
```
