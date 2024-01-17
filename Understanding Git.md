# Understanding Git

## What is Git?
Git is a distributed version control system. 

### Understanding Terms:
- **Version Control:** this is the defintion of the version control system. without version control system...
- **Distributed System:** Git is a distributed version control system, meaning that each developer has a complete copy of the entire repository (referring to the entire directory containing working directory and .git directory) on their local machine which allows for offline work and backup.

### Features of Git:
- It is widely used in software development to track changes in source code over time during the development process.
- It allows for collaboration among multiple developers on a project, helping to avoid conflicts and ensuring a consistent and organized development process.
- It provides a mechanism to revert our project back to a previous state if needed. This feature is particularly useful for undoing changes, correcting mistakes, or navigating to a specific point in your project's history.

## Understanding Terms: (also include it in feeature>>)
- **Working Directory:** It is aka Working Tree, is the directory where you are currently working on your project. It contains the files and directories that you can see and modify.
- **.git Directory:** It is the hidden directory which contains all the information Git needs to manage your project's version control, such as configuration settings. 
- **Repository:** In Git, a repository, often abbreviated as "repo", is essentially a database where Git records all the changes made to the project, including information about the change, the contributor, the timestamp of the change, and the reason for the modification. There are two main types of repositories in Git: Local and Remote Repository.
- **Local Repo:** This repository is located on your local machine. When you initialize a new Git repository within a directory, it establishes a local repository where you can execute various Git operations. This local repository is responsible for storing the complete version history of the project.
- **Remote Repo:** This is a repository that is hosted on a remote server, such as GitHub, or another Git hosting service. Remote repositories serve as a central point of collaboration for multiple developers working on the same project. Developers can push their changes to the remote repository, and others can fetch and pull those changes.

