## Git Cheat Sheet

Summary of Git commands.

### Basic Commands
* `git init` - Initialize local  Git repository.
* `git add .` - Add all files in and under current directory to git index, staging them for commit.
* `git commit -m "Message"` - Commit changes to local repo with commit message.

### Information Commands
* `git status` - Display current status of local working directory/repository.
* `git log` - List commit history.
* `git log --online` - List commit history, in a compact form.

### Branching Commands
* `git branch` - List local git branches.
* `git branch newBranch` - Create local branch `newBranch`.
* `git checkout newBranch` - Check out local branch `newBranch`.
* `git branch -M otherBranch` - Rename current branch to `otherBranch`.

### Remote Commands
* `git remote add origin remoteURL` - Add alias `origin` for remote repository URL `remoteURL`.
* `git push origin main` - Push locally-committed changes to `main` branch on remote repository.
* `git push -u origin main` - Same, setting "origin main" as default for subsequent `git push`.
