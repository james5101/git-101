# git-101

# What is a Version Control System?

A version control system, or VCS, tracks the history of changes as people and teams collaborate on projects together. Developers can review project history to find out:

 ``` 
    * Which changes were made?
    * Who made the changes?
    * When were the changes made?
    * Why were changes needed?
```

# What is a distributed version control system?

Git is an  a distributed version control system (DVCS) commonly used for open source and commercial software development. DVCSs allow full access to every file, branch, and iteration of a project, and allows every user access to a full and self-contained history of all changes. Unlike once popular centralized version control systems, DVCSs like Git don’t need a constant connection to a central repository

# What is a repository?

A repository, or Git project, encompasses the entire collection of files and folders associated with a project, along with each file’s revision history. The file history appears as snapshots in time called commits, and the commits exist as a linked-list relationship, and can be organized into multiple lines of development called branches. Because Git is a DVCS, repositories are self-contained units and anyone who owns a copy of the repository can access the entire codebase and its history.

# Basic Git Commands

Below are some of the basic/most used Git commands:
```
git init - initializes a brand new Git repository and begins tracking an existing directory.

git clone - creates a local copy of an existing project. Clone includes branches, history and all files

git add - stages a change that has been made.

git commit - saves a snapshot to the project history at a given time. Anything added with with git add will become a part of the snapshot

git status - shows status of changes

git branch - shows the branches being worked on locally

git merge - merges lines of development together. Can be used to merge 2 brnaches. Ex Feature branch to Develop branch

git pull - updates local code with its remote.

git push - updates remote with changes made
```

# Additional Training 

[Github Youtube](https://www.youtube.com/githubguides)

[Github Labs](https://lab.github.com/)

[Github Guides](https://guides.github.com/)

[Katacoda](https://www.katacoda.com/courses/git/)

[Learn Git Branching](https://learngitbranching.js.org/)
