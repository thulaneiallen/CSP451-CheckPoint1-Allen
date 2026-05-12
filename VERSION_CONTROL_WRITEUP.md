# Version Control Systems: Understanding Git and GitHub

## Introduction to Version Control

Version Control is a system that exists to track & record changes to files throughout the duration of a project so that developers are able to review, compare, restore, edit, and collaborate on the project work. 




## How Version Control Tracks Changes

Git is able to track changes through something called commits. A commit is like a checkpoint in the project history. When a developer changes a file and commits it, Git records what was changed, who made the change, when it happened, and the commit message that explains why the change was made. Each commit also gets a unique identifier called a hash, which makes it possible to find that exact point in the history later.

For example, if I create an `index.html` file and commit it with the message `feat: create basic HTML structure`, Git saves that specific version of the project. If I later update the page or break something, I can review the history to see what changed between commits.


## Three Collaboration Benefits with Examples

### 1. Branching Allows Parallel Work

Branching allows developers to work on separate features without affecting the main project. For example, one person can build the homepage while another creates an about page on a separate branch. This keeps unfinished work isolated until it is reviewed and merged.


### 2. Pull Requests Improve Code Review

Pull requests improve collaboration because they allow changes to be reviewed before they become part of the main project. For example, if I add a new page to a website, I can open a pull request so my instructor or teammate can review the code, leave comments, and approve the change before it is merged.

### 3. History Makes Mistakes Easier to Fix

Version history makes mistakes easier to fix because the team can see when a change happened and who made it. For example, if a CSS change accidentally breaks the layout of a page, the team can look through the commit history, identify the commit that caused the issue, and either fix it or reverse the change.

## Git's Backup and Recovery Mechanisms

Git stores project history inside the hidden `.git` directory. This folder contains the information Git needs to track commits, branches, and previous versions of files. Since Git is distributed, every cloned copy of a repository contains its own history. Therefore, if a local computer fails but the project was pushed to GitHub, the repository can be cloned again.

Git also provides recovery tools. Commands such as `git log`, `git reflog`, `git revert`, `git reset`, and `git fsck` help developers inspect history, find previous states, undo changes, or check repository integrity.

## Difference Between Git and GitHub

Git and GitHub are related, but they are not the same thing. Git is the version control tool that runs locally and tracks changes using commits and branches. GitHub is an online platform that hosts Git repositories and adds collaboration features such as pull requests, issues, reviews, and repository settings.

| Category | Git | GitHub |
|---|---|---|
| Type | Version control system | Online hosting platform for Git repositories |
| Location | Local computer | Cloud/web platform |
| Internet required | No for most local commands | Yes for pushing, PRs, reviews, and collaboration |
| Main purpose | Tracks changes, commits, and branches | Hosts repos and adds collaboration tools |
| Example | `git commit` | Opening a pull request |

## Conclusion

Overall, version control is important because it gives developers a safe and organized way to manage project changes. Git provides the tools for tracking, branching, and recovering work, while GitHub makes it easier to share that work with others. Together, they support a more professional and reliable workflow.

