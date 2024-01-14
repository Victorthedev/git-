# VERSION CONTROL
 This is a system that helps track and manage changes to files in a project overtime. The primary purpose of version control is to facilitate collaboration and team-work and also rovide a history of changes made to a project, it records what changes were made, who made them and when they were made.
There are two types of verson control viz;

**1. CENTRALIZED VERSION CONTROL SYSTEM (CVCS);** in this system, there is a central server that stores the entire history of the project. Developers can check out the files from the central server, make changes and update them. Examples include Subversion (SVN) and Perforce.

**2. DISTRIBUTED VERSION CONTROL SYSTEM;** here, each developer has their own coy of the entire project's repository including histories, this allows for offline work and local committed changes and sychronize when they are online. Eg: Git and Mercurial.

# BENEFITS:

**1. Collaboration:** Multiple people can work on the same project simultaneously, and the version control system manages conflict resolution and merging of changes.

**2. History and Rollback:** The system maintains a complete history of changes made to the project, allowing users to easily revert to previous versions if needed.

**3. Branching and Merging:** Version control systems allow developers to create branches, which are independent lines of development. This allows for experimentation and isolation of new features or bug fixes. Branches can later be merged back into the main project.

**4. Traceability and Accountability:** Version control systems track who made each change and when, providing a clear audit trail of contributions.

**5. Backup and Disaster Recovery:** By storing the project's history in a version control system, the risk of losing work due to hardware failures or other disasters is minimized.

# DIFFERENCES BETWEEN GIT AND GITHUB

Git is a distributed version control system, whereas GitHub is a web-based hosting service for Git repositories.

**Git:**

- Git is a distributed version control system designed to track changes to files and manage projects.
- It is a command-line tool that runs locally on a developer's machine.
- Git allows users to create repositories, track changes, create branches, merge changes, and revert to previous versions.
- It is designed for local and offline usage, meaning developers can work on their projects without an internet connection.
- Git provides features like staging changes, committing changes, and managing branches and tags.

**GitHub:**

- GitHub is a web-based hosting service that provides a platform for managing Git repositories.
- It acts as a remote repository for Git projects, allowing users to store and manage their code online.
- GitHub offers a graphical interface and additional collaboration features, making it easier for teams to work together.
- It provides a central hub for developers to share their code, collaborate with others, and contribute to open-source projects.
- GitHub offers additional features like issue tracking, pull requests, code reviews, and project management tools.
- It allows developers to showcase their work, collaborate with others, and contribute to the open-source community.

# ALTERNATIVES TO GITHUB

- SourceForge
- Gitlab
- Bitbucket

# DIFFERENCE BETWEEN GIT FETCH AND GIT PULL

**1. git fetch:** This command retrieves new commits, branches, and tags from a remote repository to your local repository. It updates the remote-tracking branches in your local repository, allowing you to see the changes made by others without modifying your current branch. The fetched changes are stored locally but are not automatically merged with your working branch.

   `git fetch` is useful for reviewing changes made by others before deciding to incorporate them into your work. It updates your local copy of the remote repository without modifying your current working branch.

**2. git pull:** This command is a combination of two actions: `git fetch` followed by `git merge`. It retrieves new commits from a remote repository and automatically merges them into your current working branch.

   Essentially, `git pull` fetches the remote changes and immediately merges them into your current branch. If there are no conflicts, the merge is done automatically. However, if there are conflicts between the remote changes and your local changes, you will need to resolve them manually.

   `git pull` is commonly used to update your local branch with the remote changes and incorporate them into your work.

   # GIT REBASE AND ITS COMMAND

   `git rebase` is a command in Git that allows you to integrate the changes from one branch onto another branch. It restructures the commit history, making it appear as if the changes were made directly on the branch you're rebasing onto.

To perform a git rebase:

`git rebase <branch>`

# GIT CHERRY-PICK AND ITS COMMAND

`git cherry-pick` is a Git command that allows you to pick and apply specific commits from one branch and apply them to another branch.

To perform a git cherry-pick

`git cherry-pick <commit>`
