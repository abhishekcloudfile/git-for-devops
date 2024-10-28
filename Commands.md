Git Commands Reference
1. Repository Setup
Initialize a Repository
git init - Initializes a new Git repository in the current directory.
2. User Configuration
Set User Information
git config --global user.name "YourUsername" - Sets the global Git username.
git config --global user.email "youremail@example.com" - Sets the global Git email.
3. Tracking Changes
Staging Changes
git add <file> - Stages changes in the specified file.
Committing Changes
git commit -m "Your commit message" - Commits all staged changes with a message.
4. Working with Branches
Branch Management
git branch - Lists all branches in the repository.
git checkout -b <branch-name> - Creates and switches to a new branch.
git switch <branch-name> - Switches to the specified branch.
5. Repository Status and Logs
View Status
git status - Shows the current status of the working directory and staging area.
View Commit History
git log - Shows the full commit history.
git log --oneline - Shows a condensed commit history.
6. Undoing Changes
Unstage Changes
git rm --cached <file> - Unstages a file without deleting it from the working directory.
Discard Changes
git restore <file> - Discards changes in the working directory.
7. Removing Files
Remove a File from Repository
git rm <file> - Deletes the file from the working directory and stages the deletion.
8. Remote Repositories
Add and Manage Remotes
git remote add origin <url> - Adds a new remote repository.
git fetch origin - Fetches updates from the remote repository.
Push and Pull Changes
git push origin <branch-name> - Pushes committed changes to the remote repository.
git pull origin <branch-name> - Pulls updates from the remote repository.
9. Merging and Rebasing
Merging Branches
git merge <branch-name> - Merges the specified branch into the current branch.
Rebasing Branches
git rebase <branch-name> - Rebases the current branch onto the specified branch.
10. Viewing Differences
Compare Changes
git diff - Shows changes in the working directory that haven’t been staged.
git diff <commit1> <commit2> - Shows differences between two commits.
11. Additional Commands
View Command History
history - Displays a list of recent commands executed in the terminal.
