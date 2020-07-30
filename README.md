# 2020-07-30-git_collaboration-cora
Git collaboration notes

- `git clone <url>` : downloads the repository from the web to your local computer
    - make sure your don't nest this command into another repository
    - just like `git init` , only do this once per repo

- `git branch <branch_name>`: create a new branch where HEAD is
    - ` git branch -a `: list all branches your local machine knows of
- `git switch <branch_name>` : move to branch
    - `git checkout <branch_name>`: the pre-August 2019 way

- `git switch -c <branch_name>` : create a new branch where HEAD is
   - `git checkout -b <branch_name>`

- `git log --oneline --graph --decorate --all`: shows you your git history tree
   - you can look up how to set this as an git alias

- `git fetch --prune` : clean your git history, and remove references from remote that no longer exists

- `git branch -d <branch_name>` : remove branch from your local computer 

- Pull request: when you push a branch to the remote and merge the branch in the online interface


