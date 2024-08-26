# Top 50 Most Used Git Commands
![image](https://github.com/user-attachments/assets/3d707073-4acb-4d6d-a519-76af029b6c42)

## Repository Setup
1. **git init**: Initialize a new Git repository
2. **git clone [URL]**: Clone an existing repository
3. **git remote add origin [URL]**: Add a remote repository
4. **git remote -v**: List remote repositories
5. **git config --global user.name "[name]"**: Set the global username for commits
6. **git config --global user.email "[email]"**: Set the global email for commits
7. **git config --global core.editor [editor]**: Set the default editor for Git

## Basic Workflow
8. **git status**: Show the working directory status
9. **git add [file]**: Stage changes for commit
10. **git add \***: Stage all changes for commit
11. **git commit -m "[message]"**: Commit staged changes with a message
12. **git commit -a -m "[message]"**: Stage and commit all changes in one step
13. **git push origin [branch]**: Push changes to the remote repository
14. **git pull**: Fetch and merge changes from the remote repository
15. **git fetch**: Fetch changes from the remote repository without merging
16. **git log**: View commit history
17. **git log --oneline**: View a simplified commit history
18. **git show [commit]**: Show details of a specific commit
19. **git diff**: Show changes between commits, branches, or working directory
20. **git diff --staged**: Show changes between staged files and the last commit

## Branching
21. **git branch**: List all local branches
22. **git branch [branch-name]**: Create a new branch
23. **git checkout [branch-name]**: Switch to an existing branch
24. **git checkout -b [branch-name]**: Create and switch to a new branch
25. **git merge [branch-name]**: Merge a branch into the current branch
26. **git branch -d [branch-name]**: Delete a local branch
27. **git push origin --delete [branch-name]**: Delete a remote branch
28. **git branch -r**: List all remote branches
29. **git branch -a**: List all branches (local and remote)

## Undoing Changes
30. **git reset [file]**: Unstage a file, keeping its changes
31. **git reset --hard [commit]**: Reset the working directory and index to a specific commit, discarding changes
32. **git revert [commit]**: Create a new commit that undoes a previous commit
33. **git checkout -- [file]**: Discard changes in a working directory
34. **git stash**: Save changes temporarily to switch branches
35. **git stash pop**: Apply the most recent stash and remove it from the stash list
36. **git stash list**: List all stashed changes

## Collaboration
37. **git push**: Push changes to the remote repository
38. **git pull**: Fetch and merge changes from the remote repository
39. **git push --force**: Force-push changes, overwriting remote history
40. **git push --set-upstream origin [branch]**: Set a remote branch to track with a local branch
41. **git remote show origin**: Show information about the remote repository

## Tags
42. **git tag [tag-name]**: Create a new tag
43. **git tag -a [tag-name] -m "[message]"**: Create an annotated tag with a message
44. **git tag -d [tag-name]**: Delete a local tag
45. **git push origin [tag-name]**: Push a tag to the remote repository
46. **git push origin --delete [tag-name]**: Delete a remote tag

## Aliases & Configuration
47. **git config --global alias.st status**: Create an alias for `git status`
48. **git config --global alias.co checkout**: Create an alias for `git checkout`
49. **git config --global alias.ci commit**: Create an alias for `git commit`
50. **git config --global alias.br branch**: Create an alias for `git branch`
