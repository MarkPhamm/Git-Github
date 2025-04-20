# Exploring Git commands
A practical reference guide to help you understand and navigate the most commonly used Git commands — from setup to collaboration.

<img src="https://github.com/user-attachments/assets/3d707073-4acb-4d6d-a519-76af029b6c42" width="100%"/>

---

## Repository Setup

1. `git init` — Initialize a new Git repository  
2. `git clone [URL]` — Clone an existing repository  
3. `git remote add origin [URL]` — Add a remote repository  
4. `git remote -v` — List remote repositories  
5. `git config --global user.name "[name]"` — Set the global username for commits  
6. `git config --global user.email "[email]"` — Set the global email for commits  
7. `git config --global core.editor [editor]` — Set the default editor for Git  
8. `git config user.name "[name]"` — Set the local username for the current repository  
9. `git config user.email "[email]"` — Set the local email for the current repository  
10. `git config --list` — List all Git config values  
11. `git config --list --show-origin` — Show config values with the source file

---

## Basic Workflow

12. `git status` — Show the working directory status  
13. `git add [file]` — Stage changes for commit  
14. `git add *` — Stage all changes for commit  
15. `git commit -m "[message]"` — Commit staged changes with a message  
16. `git commit -a -m "[message]"` — Stage and commit all changes in one step  
17. `git push origin [branch]` — Push changes to the remote repository  
18. `git pull` — Fetch and merge changes from the remote repository  
19. `git fetch` — Fetch changes from the remote without merging  
20. `git log` — View commit history  
21. `git log --oneline` — View simplified commit history  
22. `git show [commit]` — Show details of a specific commit  
23. `git diff` — Show changes between commits, branches, or working directory  
24. `git diff --staged` — Show changes between staged files and the last commit  

---

## Branching

25. `git branch` — List all local branches  
26. `git branch [branch-name]` — Create a new branch  
27. `git checkout [branch-name]` — Switch to an existing branch  
28. `git checkout -b [branch-name]` — Create and switch to a new branch  
29. `git merge [branch-name]` — Merge a branch into the current branch  
30. `git branch -d [branch-name]` — Delete a local branch  
31. `git push origin --delete [branch-name]` — Delete a remote branch  
32. `git branch -r` — List all remote branches  
33. `git branch -a` — List all branches (local and remote)  

---

## Undoing Changes

34. `git reset [file]` — Unstage a file, keeping its changes  
35. `git reset --hard [commit]` — Reset working directory and index to a specific commit  
36. `git revert [commit]` — Create a new commit that undoes a previous one  
37. `git checkout -- [file]` — Discard changes in a file  
38. `git stash` — Save changes temporarily to switch branches  
39. `git stash pop` — Reapply the most recent stash and remove it  
40. `git stash list` — List all stashed changes  

---

## Collaboration

41. `git push` — Push changes to the remote repository  
42. `git pull` — Fetch and merge changes from the remote repository  
43. `git push --force` — Force-push changes, overwriting history  
44. `git push --set-upstream origin [branch]` — Track a remote branch with your local branch  
45. `git remote show origin` — Show detailed info about the remote repo  

---

## Tags

46. `git tag [tag-name]` — Create a new tag  
47. `git tag -a [tag-name] -m "[message]"` — Create an annotated tag with a message  
48. `git tag -d [tag-name]` — Delete a local tag  
49. `git push origin [tag-name]` — Push a tag to the remote repository  
50. `git push origin --delete [tag-name]` — Delete a remote tag  

---

## Aliases & Configuration

51. `git config --global alias.st status` — Create alias `st` for `git status`  
52. `git config --global alias.co checkout` — Create alias `co` for `git checkout`  
53. `git config --global alias.ci commit` — Create alias `ci` for `git commit`  
54. `git config --global alias.br branch` — Create alias `br` for `git branch`  

---
