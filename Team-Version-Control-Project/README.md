
# Team Version Control Project

## Aim
To implement collaborative version control using Git and GitHub by creating branches, managing commits, reviewing pull requests, merging changes, and resolving merge conflicts.

## Tools Used
- Git
- GitHub
- Visual Studio Code

## Project Modules
- **Module 1:** Greeting functionality
- **Module 2:** Project status functionality
- **Module 3:** Project summary functionality

## Branching Strategy
The `main` branch contains the stable project version. Separate feature branches were created for individual modules.

| Branch | Purpose |
|---|---|
| `main` | Stable project version |
| `feature/module1` | Module 1 development |
| `feature/module2` | Module 2 development |
| `feature/module3` | Module 3 development |
| `feature/member1-conflict` | First conflicting change |
| `feature/member2-conflict` | Second conflicting change |

## Version Control Workflow
1. Initialized a local Git repository.
2. Added project files and created the initial commit.
3. Connected the local repository to GitHub.
4. Created individual feature branches for modules.
5. Committed and pushed changes to the corresponding branches.
6. Created pull requests targeting `main`.
7. Reviewed the changes before merging.
8. Merged approved pull requests into `main`.
9. Created conflicting edits in two branches.
10. Resolved the merge conflict and committed the resolution.

## Merge Conflict Resolution
A merge conflict was demonstrated by modifying the same line in `conflict-practice.txt` on two branches. Git identified the conflicting changes during merging. The conflict was manually resolved by combining both contributions, followed by staging and committing the resolved file.

## Conclusion
The experiment demonstrated Git and GitHub collaboration through repository creation, branch management, commits, pull requests, code review, merging, and merge conflict resolution.
