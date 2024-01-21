# Git & Github PASC SIG

Git and Github SIG was conducted on 19-Jan-2023 for the First Year and Second Year Students. This repo contains all the material related that.

#### Basic Commands

`git init`
    Initializes a new Git repository in the current directory.

`git clone [repository_url]`
    Creates a copy of a remote repository on your local machine.

`git add [file(s)]`
    Adds changes in the working directory to the staging area.

`git commit -m "Commit message"`
    Commits changes from the staging area to the repository with a descriptive message.

`git status`
    Shows the status of changes as untracked, modified, or staged.

#### Branching and Merging

`git branch`
    Lists all branches in the repository.

`git branch [branch_name]`
    Creates a new branch.

`git checkout [branch_name] or git switch [branch_name]` (Git 2.23+)
    Switches to the specified branch.

`git merge [branch_name]`
    Merges changes from the specified branch into the current branch.

`git pull`
    Fetches changes from the remote repository and merges them into the current branch.

`git push`
    Pushes local commits to the remote repository.

#### Remote Repositories

`git remote add [remote_name] [repository_url]`
    Adds a remote repository.

`git remote -v`
    Lists all remote repositories.

`git fetch [remote_name]`
    Fetches changes from the remote repository.

`git pull [remote_name] [branch_name]`
    Fetches changes and merges them into the current branch.

`git push [remote_name] [branch_name]`
    Pushes changes to the specified remote branch.

#### Undoing Changes

`git reset [file]`
    Unstages changes.

`git revert [commit]`
    Creates a new commit that undoes the specified commit.

`git checkout -- [file]`
    Discards changes in the working directory for the specified file.

`git reset --hard [commit]`
    Discards all changes after the specified commit.

#### Additional Commands

`git log`
    Displays the commit history.

`git diff`
    Shows the differences between the working directory and the repository.

`git config`
    Configures Git settings either globally or per repository.

`git tag [tag_name]`
    Creates a tag for a specific commit.

`git stash`
    Temporarily saves changes that are not ready to be committed.
