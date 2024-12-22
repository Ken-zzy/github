# github

## Version Control

Version control is the practice of tracking and managing changes to software code. This is used by developers to keep track of changes made to their codes and it helps to organise and control multiple versions of the same code.

## Git:
 Git is a version control software that helps programeres keep track of their codes and is independent of Github, it is a powerful command-line tool for tracking changes to files that runs locally on your computer.

## GitHub:
Github is a software that is used to manage the progress saved on Git, it makes navigating through saved repositories easier and is dependent on Git, it offers features like issue tracking, pull requests, and collaboration tools.

## GitHub Alternatives

1.  GitLab
2.  Bitbucket
3.  Azure DevOps

## git fetch:
Gitfetch downloads data from the online reprository to your local device but doesn't try to merge it with your work

## git pull:  
Gitpull downloads data from the online reprository and automaticaly tries to merge it with with the code you're currently working on it performs both git fetch and git merge in a single step.

## Git Rebase
 
Rebasing is when you take all the changes that were committed on one branch and apply them on a different branch it creates a cleaner, more linear commit history.

Command: git rebase <target_branch> (e.g., git rebase main)

## Git Cherry-pick

git cherry-picking is choosing a commit from one branch and applying it to another, it selectively applies a single commit from another branch to your current branch.

Command: git cherry-pick <commit_hash> (e.g., git cherry-pick <commit_id>)