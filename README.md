
## VERSION CONTROL SYSTEM

A Version Control System (VCS) is a tool used in software development and collaborative projects to track and manage changes to source code. It allows developers to:

- Record and track every update to the codebase
- Collaborate on code without overwriting each other's work
- Revert to earlier states of the project if needed
- Maintain a detailed and structured history of the project’s evolution


## WORKING OF VERSION CONTROL SYSTEM

![image](https://github.com/nirmaltej2003/Git-Skill-Up/blob/main/Screenshot%202026-02-08%20080357.png)

- The repository stores the project files on a server
- Multiple developers connect to the repository
- Developers access and update files to collaborate
- Changes made by one developer can be shared with others
- This setup maintains a centralized or distributed project history


## COMPONENTS OF VERSION CONTROL SYSTEMS

Repository
- A central location that stores all project files
- Maintains complete change history and metadata such as author and commit message

Revision
- A specific saved version of a file or project
- Identified using a unique ID such as a number or hash

Branch
- A separate copy of the codebase
- Used to develop features or fix bugs independently

Merging
- Combines changes from one branch into another
- May require resolving conflicts

Commit
- A snapshot of changes at a specific time
- Used to track project history


## TYPES OF VERSION CONTROL SYSTEMS

1️⃣ **Local Version Control System (Local VCS)**

A Local Version Control System works only on a personal machine. All changes and version history are stored locally.

Characteristics:
- No internet or server dependency
- Suitable for individual projects
- Limited to single-user environments
- No collaboration support

2️⃣ **Centralized Version Control System (CVCS)**

In a centralized system, all files and their history are stored on a single central server.

Workflow:
- Update or Checkout: Developer pulls latest files
- Make Changes: Developer edits files locally
- Commit: Changes are saved directly to the server

Advantages:
- Easy collaboration
- Centralized control and permissions

Disadvantages:
- Single point of failure
- If server goes down, work is blocked

Examples:
- SVN
- CVS

3️⃣ **Distributed Version Control System (DVCS)**

In distributed systems, each developer has a local repository and working copy.

Key points:
- Commit saves changes locally
- Push uploads changes to central repository
- Pull or Fetch downloads changes from others

Workflow:
- Commit → Push
- Fetch / Pull → Update local repository

Advantages:
- No single point of failure
- Offline work supported
- Faster operations

Examples:
- Git
- Mercurial

## POPULAR VERSION CONTROL SYSTEMS

1️⃣ **Git**

Git is a distributed version control system developed by Linus Torvalds in 2005 for managing the Linux kernel. It is widely used in modern software development.

Features:
- Lightweight, fast and efficient
- Easy branching and merging
- Supports commands like git clone, git pull and git push
- Backbone of GitHub, GitLab and Bitbucket

2️⃣ **Subversion (SVN)**

Subversion is a centralized version control system commonly used in enterprises.

Features:
- Single central repository
- Supports branching and tagging
- Versions both files and directories

3️⃣ **Mercurial**

Mercurial is a distributed version control system similar to Git with a simpler interface.

Features:
- Simple, fast and scalable
- Supports branching and merging
- Suitable for small and large projects

4️⃣ **CVS (Concurrent Versions System)**

CVS is one of the earliest centralized version control systems.

Features:
- Centralized repository
- Tracks changes to individual files
- Supports basic branching and tagging
- Foundation for later tools like SVN and Git

5️⃣ **Bazaar**

Bazaar is a distributed version control system developed by Canonical.

Features:
- Supports both centralized and distributed models
- Beginner-friendly commands
- Cross-platform support
- Used in projects like Ubuntu and MySQL

# Centralized Vs Distributed Version Control

Version control enables organized code management and collaboration.
There are two main types of version control systems:
1. Centralized Version Control (CVCS)
2. Distributed Version Control (DVCS)

The choice depends on the nature and scale of the project.

## 1️⃣ Centralized Version Control (CVCS)

Centralized Version Control (CVCS) uses a single central repository
where all project code is stored. Developers access this repository
to make changes.

Examples: SVN, CVS

### Features of CVCS
- Single central repository for all files
- Centralized version history
- Real-time collaboration
- Simple to set up and understand

### Use Cases of CVCS
- Small teams working closely
- Projects needing real-time code access
- Organizations requiring strict control


## 2️⃣ Distributed Version Control (DVCS)

Distributed Version Control (DVCS) allows each developer to have
a complete local copy of the repository, including full history.

Examples: Git, Mercurial, Bazaar

### Features of DVCS
- Complete local repositories
- Offline work and local commits
- Easy branching and merging
- No single point of failure
- Decentralized collaboration

### Use Cases of DVCS
- Large or distributed teams
- Open-source projects
- Projects needing frequent branching and merging
  

## CVCS vs DVCS Comparison

| Centralized Version Control (CVCS) | Distributed Version Control (DVCS) |
|----------------------------------|-----------------------------------|
| Single central repository        | Full repository for each developer |
| Server needed for commits        | Offline commits possible           |
| Slower operations               | Faster local operations            |
| Harder branching and merging    | Easy branching and merging         |
| Single point of failure         | No single point of failure         |
| Best for small teams            | Best for large and distributed teams |

