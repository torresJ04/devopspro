# GIT & GITHUB TOOLKIT - DEVOPS PRO
### Scopes
`--global` -> overwrittes system scope.

### Local setup Git
`git config --list` -> List current configs for git.  
`git config --global user.name "Your username"` -> A common username.  
`git config --global user.mail <Your github email>` -> Your github email.  
`git config --global core.editor <Your preferred editor>` -> A code editor, like VIM.  
`git config --global init.defaultBranch main` -> Set main as default branch.  
`git init` -> Creates a git repository inside of the current directory.

### Branching
`git branch` -> List all branches in your repository.  
`git branch <branch_name>` -> Create a new branch.  
`git checkout <branch_name>` -> Switch to the specified branch.  
`git checkout -b <branch_name>` -> Create and switch to a new branch.  
`git branch -d <branch_name>` -> Delete a branch.  
`git merge <branch_name>` -> Merge the specified branch into the current branch.

### Staging and Committing
`git status` -> Show the working tree status.  
`git add <file>` -> Stage a file.  
`git add .` -> Stage all changes in the current directory.  
`git commit -m "Commit message"` -> Commit staged changes with a message.  
`git commit -am "Commit message"` -> Stage and commit all changes with a message.  
`git reset <file>` -> Unstage a file.  
`git reset --hard` -> Reset the working directory and staging area to the last commit.

### Remote Repositories
`git remote -v` -> List remote repositories.  
`git remote add <name> <url>` -> Add a remote repository.  
`git fetch <remote>` -> Fetch changes from a remote repository.  
`git pull <remote>` -> Fetch and merge changes from a remote repository.  
`git push <remote> <branch>` -> Push changes to a remote repository.

### Viewing History
`git log` -> Show commit logs.  
`git log --oneline` -> Show commit logs in a single line.  
`git log --graph --oneline` -> Show commit logs as a graph.  
`git show <commit>` -> Show changes in a specific commit.  
`git diff` -> Show changes between commits, commit and working tree, etc.  
`git diff <commit>` -> Show changes between the working tree and a specific commit.  
`git blame <file>` -> Show who changed each line of a file.

### Undoing Changes
`git revert <commit>` -> Revert a specific commit.  
`git cherry-pick <commit>` -> Apply the changes introduced by a specific commit.  
`git stash` -> Stash changes in a dirty working directory.  
`git stash list` -> List all stashes.  
`git stash apply` -> Apply the latest stash.  
`git stash drop` -> Drop the latest stash.

### Tags
`git tag` -> List tags.  
`git tag <tag_name>` -> Create a tag.  
`git tag -d <tag_name>` -> Delete a tag.  
`git push <remote> <tag_name>` -> Push a tag to a remote repository.

### Submodules
`git submodule add <url> <path>` -> Add a submodule.  
`git submodule init` -> Initialize submodules.  
`git submodule update` -> Update submodules.

### Miscellaneous
`git archive --format=zip --output=<file.zip> <commit>` -> Create a zip archive of a repository.  
`git bisect start` -> Start a bisect session.  
`git bisect bad` -> Mark the current commit as bad.  
`git bisect good <commit>` -> Mark a commit as good.
