GIT: stores this information in a data structure called a repository

GITHUB: Git client, another popular git client is GitLab

Repository: A place where files are stored that are accessable anwhere by anyone with permission.

Clone: git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository
Example: git clone "git_repo"

Commit: tracks modifications of a fie
Example: git commit -m "example commit message"

Push: Push commits to remote repository
Example: git push origin master - pushes local repo to origin master branch (remote branch)

Pull: Update local repository to the newest commit
Example: git pull master, pulls the remote repo to local repo

Branch: a seperate working copy of the master git repository, used when adding features to the master branch without interfering with other colaborators local versions.
Example: "git branch -a"  lists all branches
Example: git branch new-branch -This creates a new branch

Merge: used to add a feature branch back into master.
Example: git merge master - merges the current branch to master

Merge Conflict: Happens when the master branch and feature branch have conflicting code. Use an editor with a nice merge tool to make merge conflicts easy to fix.
Example: use git status to check conflicts 

Fetch: Get the latest version of the remote repo

Remote: The code that lives on github/gitlab

References:
https://www.sbf5.com/~cduan/technical/git/git-1.shtml
https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud

