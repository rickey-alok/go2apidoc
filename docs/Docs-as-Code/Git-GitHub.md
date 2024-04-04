# Git & GitHub - Cheat sheet

## Git

!!! info inline end ""

    ![image](https://rickey-alok.github.io/api-go-to-doc/img/git-logo.png)

### What is Git?

- an open source
  - so it is free to use and developers can modify the source code to suit their needs
- distributed version-control system, for software development mainly
  - meaning there is no central point of control
  - every computer is a full-fledged repository with complete history and full version-tracking abilities
- but not a programming language
- developed by **Linus Torvalds** in 2005

### Why do we use Git?

- Collaboration
  - allows multiple developers to work on the same project at the same time without interfering with one another
- Branching
  - allows developers to create branches of a project, so they can make changes without affecting the main version of the project
- Speed
  - fast and efficient system which allows developers to work quickly and seamlessly on projects
- Security
  - uses encryption to secure data transfer and storage, which helps keep sensitive information safe

## GitHub

!!! info inline end ""

    ![alt text](image-1.png)

### What is GitHub?

- A platform for code hosting and collaborating on projects using git
- It serves as a location for uploading copies of a Git repository

### Why do we use GitHub?

- makes it easy for developers to share code files and collaborate with fellow developers
- also serves as a social networking site where developers can openly network, collaborate, and pitch their work

### Git and GitHub workflow

At first, I use to struggle to grasp the intricacies of Git and GitHub workflows via command lines. Despite encountering numerous resources available on the internet that discussed these activities, their explanations remained unclear. So, I decided to simplify the process. After using these commands extensively, I created a visual workflow that explains the purpose of each command and makes them easier to remember.

## Git Commands

Git offers a plethora of commands, but some are used only occasionally (One time commands) — when setting up our IDE and some are used Frequently as part of our daily work routine.

### One time commands

- **[git init]:** initialize an existing directory as a Git repository
- **[git config --global user.email "xyz@gmail.com"]**: set an email address that will be associated with each history marker
- **[git config --global user.name "yourName"]**: set a name that is identifiable for credit when review version history
- **[git remote add origin "url - http or SHH"]**: add a remote repository
- **[git clone "url - http or SHH"]**: retrieve an entire repository from a hosted location via URL

  !!! note

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
        nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
        massa, nec semper lorem quam in massa.

??? note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
