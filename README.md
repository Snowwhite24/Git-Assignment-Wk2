# Git-Assignment-Wk2

## Explain version control
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It is the practice of tracking and managing changes to software code. This is done through VCs that are software tools that help software teams, manage changes such that if a mistake is made, developers can track or locate the it in earlier versions of the file by  comparing them.

## Expalin the difference between Git and Github
Git is a distributed version control control system for tracking changes in source code during software development and it allows programmers to work together and track changes in any set of files. github is a web-based Git repository hosting service which has a built-in user management feature. it has an active market place for tool integration.

## List 3 other Github alternatives
- Bitbucket
- Gitea
- Gitlab

## Explain the difference between git fetch and git pull
"git fetch"is a command that updates local mirror of a remote repository. It downloads new commits from the remote repository and updates the reference remote to match their counterpart in the remote repository. "git pull" is a command that fetches changes from the remote and merges the current branch with its upstream.

## Explain in simple terms git rebase and the command for it
"git rebase" is a way of integrating changes from one branch to another. it allows you to reapply all the changes made to a new branch to an older branch.
command: git rebase [base_name] or git rebase -- onto master branch

# Explain in the simple terms git cherry-pick and the command for it
"git cherry-pick" is used for merging  a single commit. It takes the patch that was introducedina commit and reapply it on the current branch
command: git cherry-pick [branch_name]