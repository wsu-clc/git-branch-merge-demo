# Git Branch and Merge Demo
Weber State University's accompanying repository for the Creating and Managing Branches, Simple Merging, Merging and Conflict Resolution, and Pull Requests and Cleanup tutorial videos.
## Creating and Managing Branches
In this video, you will isolate development environments by creating branches, navigate between project states by switching between branches, and manage repository clutter by deleting branches.
* Use `git branch` to check what branch you are on and see all branches.
* Use `git branch branch-name` with a descriptive name to create a new branch.
* Use `git switch branch-name` to switch to a branch.
* Use `git switch -c branch-name` to create and switch to a branch with a single command.
* Use `git branch -d` to perform a safe delete (if changes have been merged or if branch has no commits).
* Use `git branch -D` to perform a force delete (if branch has unmerged commits).
## Simple Merging
In this video, you will perform a fast-forward merge to update a branch, execute a three-way merge to combine separate timelines, and identify how Git automatically handles merge commits.
* Use `git status` to check your current working tree state and branch. 
* Use `git switch main` to switch back to your production branch.
* Use `git merge feature/navbar` to execute a linear fast-forward merge.
* Use `cat index.html` to view the file contents directly inside your terminal.
* Use `git switch feature/footer` to navigate to a divergent feature branch.
* Use `git add index.html` to stage file changes for the next commit.
* Use `git commit -m “Add footer layout”` to save staged changes with a message.
* Use `git switch main` to return to the production branch before merging.
* Use `git merge feature/footer` to trigger a three-way merge and generate a merge commit.
## Merging and Conflict Resolution
In this video, you will trigger a merge conflict by modifying identical lines of code across different branches, analyze and resolve the conflict, and finalize your history by pushing the clean code to GitHub.
* Use `git status` to view unmerged paths and check the state of your working tree.
* Use `git branch feature/headline` to create a new feature branch while staying on your current branch.
* Use `git add index.html` to stage the modified file after making your changes or resolving conflicts.
* Use `git commit -m "Add official welcome headline on main"` to commit changes directly to the main branch.
* Use `git switch feature/headline` to switch over to your new feature branch.
* Use `git commit -m "Add project discovery headline on feature branch"` to save the competing changes on your feature branch.
* Use `git switch main` to return to the main branch prior to merging.
* Use `git merge feature/headline` to attempt a merge and intentionally trigger a merge conflict.
* Use `git commit -m "Merge branch 'feature/headline' and resolve headline conflict"` to finalize the merge after resolving the conflict.
* Use `git push origin main` to upload your locally unified main branch history to your remote GitHub repository.
## Pull Requests and Cleanup
In this video, you will initiate collaborative code reviews by creating a Pull Request on GitHub, safely decommission stale development environments by deleting local branches, and reset your local repository to a clean slate.
* Use `git branch` to list all existing branches and see which one is currently active.
* OR Use `git status` to check your current branch state and ensure you have a clean working tree.
* Use `git switch` if you need to switch branches, to ensure you are on the production branch before removing finished features.
* Use `git branch -d feature/navbar feature/footer feature/headline` to safely delete multiple local feature branches after their histories have been integrated.
* Use `git status` to ensure your work environment is clean. 

