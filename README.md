# Git Commands Cheat Sheet

## Basic Workflow
1. **cd**: Change directory
2. **mkdir**: Create a directory
3. **git init**: Initialize a Git repository (.git directory)
4. **git add [file]**: Stage specified file(s) for commit
5. **git add \***: Stage all files for commit
6. **git status**: Check the status of files (modified, new, staged)
7. **git commit -m "message"**: Commit changes with a message
8. **git remote add origin [URL]**: Link to a remote repository
9. **git push origin [branch]**: Push changes to GitHub
10. **git clone [URL]**: Clone a Git repository

## Branching
11. **git branch [branch]**: Create a new branch
12. **git branch -D [branch]**: Delete a branch
13. **git checkout [branch]**: Switch to an existing branch
14. **git checkout -b [branch]**: Create and switch to a new branch
15. **git branch -r**: List all remote branches
16. **git branch -d [branch]**: Delete a local branch
17. **git push origin --delete [branch]**: Delete a remote branch
18. **git stash**: Save work without committing, to switch branches
19. **git stash -u**: Stash untracked files

## Deleting & Restoring Files
20. **git rm [file]**: Delete a file locally
21. **git add [file]**: Stage a deleted file
22. **git add -u**: Stage all changes (including deletions)
23. **git restore [file]**: Restore a deleted file before commit
24. **git checkout HEAD^ [file]**: Restore a deleted file after commit
