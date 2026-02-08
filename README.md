
VERSION CONTROL SYSTEM
--------------------------------------------------

A Version Control System (VCS) is a tool used in software development and collaborative projects to track and manage changes to source code. It allows developers to:

- Record and track every update to the codebase
- Collaborate on code without overwriting each other's work
- Revert to earlier states of the project if needed
- Maintain a detailed and structured history of the project’s evolution


WORKING OF VERSION CONTROL SYSTEM
--------------------------------------------------

- The repository stores the project files on a server
- Multiple developers connect to the repository
- Developers access and update files to collaborate
- Changes made by one developer can be shared with others
- This setup maintains a centralized or distributed project history


COMPONENTS OF VERSION CONTROL SYSTEMS
--------------------------------------------------

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


TYPES OF VERSION CONTROL SYSTEMS
--------------------------------------------------

1. **Local Version Control System (Local VCS)**

A Local Version Control System works only on a personal machine. All changes and version history are stored locally.

Characteristics:
- No internet or server dependency
- Suitable for individual projects
- Limited to single-user environments
- No collaboration support



2. **Centralized Version Control System (CVCS)**

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



3. **Distributed Version Control System (DVCS)**

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


POPULAR VERSION CONTROL SYSTEMS
--------------------------------------------------

1. **Git**

Git is a distributed version control system developed by Linus Torvalds in 2005 for managing the Linux kernel. It is widely used in modern software development.

Features:
- Lightweight, fast and efficient
- Easy branching and merging
- Supports commands like git clone, git pull and git push
- Backbone of GitHub, GitLab and Bitbucket



2. **Subversion (SVN)**

Subversion is a centralized version control system commonly used in enterprises.

Features:
- Single central repository
- Supports branching and tagging
- Versions both files and directories



3. **Mercurial**

Mercurial is a distributed version control system similar to Git with a simpler interface.

Features:
- Simple, fast and scalable
- Supports branching and merging
- Suitable for small and large projects



4. **CVS (Concurrent Versions System)**

CVS is one of the earliest centralized version control systems.

Features:
- Centralized repository
- Tracks changes to individual files
- Supports basic branching and tagging
- Foundation for later tools like SVN and Git



5. **Bazaar**

Bazaar is a distributed version control system developed by Canonical.

Features:
- Supports both centralized and distributed models
- Beginner-friendly commands
- Cross-platform support
- Used in projects like Ubuntu and MySQL

