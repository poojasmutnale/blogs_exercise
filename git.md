# Git : Version Control System

Git is an actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel. A large number of software projects rely on Git for version control, including commercial projects as well as open source.

## What is [Git](https://en.wikipedia.org/wiki/Git)?

**Git** is a powerful and widely-used version control system that allows developers to track changes in their code, collaborate effectively.

> Unlike centralized version control systems, Git allows each developer to have a complete copy of the repository, including its entire history. This distributed nature enhances collaboration and ensures that the project history is resilient against data loss.

> [!NOTE]
> While most people confuse Git with Github, it is important to note that both are note the same. 

[![The Difference between Git and Github](https://www.hubspot.com/hs-fs/hubfs/git%20vs%20github.webp?width=650&height=450&name=git%20vs%20github.webp)](https://www.geeksforgeeks.org/difference-between-git-and-github/)

## Some basic Commands

To use Git, developers use specific commands to copy, create, change, and combine code.

- **`git init`:** 
    - Initialize a new git repository. This is the first command you should run when starting a new project

- **`git clone`:**
    - Clone an existing git repository. This command allows you to create a local copy of a remote repository.

- **`git add`:** 
    - Add files to a repository. This command allows you to add new files or changes to already existing files to a git repository.

- **`git commit`:** 
    - Make changes to a repository. This command saves your changes to the git history.

- **`git push`:** 
    - Push changes to a git remote repository. This command pushes your local commits to a remote git repository.

- **`git pull`:** 
    - Pull changes from a git remote repository. This command pulls down any remote changes and incorporates them into your local git repository.

- **`git status`:** 
    - Check the status of your git repository. This will let you know which files have been modified and which files are being tracked by git.

- **`git log`:** 
    - View the commit history for your git repository. This is useful for finding out when certain changes were made and who made them.

- **`git reset`:**
    - Reset your git repository to a specific commit. This command allows you to undo changes to a file or reset your git history.

## Basic Git Workflow

1. **Clone a Repository:**
    - To start working on an existing project, clone the repository to your local machine.
    ```
    git clone https://github.com/username/repository.git
    ```

2. **Create a Branch:**
    - Create a new branch for your work to keep the main branch stable.
    ```
    git checkout -b new-feature
    ```
    
3. **Make Changes and Commit:**
    - After making changes to the code, add them to the staging area and commit.
    ```
    git add .
    git commit -m "Implement new feature"
    ```

4. **Push Changes:**
    - Push your changes to the remote repository to share them with others.
    ```
    git push origin new-feature
    ```

5. **Open a Pull Request:**
    - On platforms like GitHub, open a pull request to propose merging your changes into the main branch. This allows others to review and discuss your code before it is merged.

## Conclusion

Git is an inseperable tool for any software development firm or developer.Whether you're a beginner just starting out or an experienced developer, mastering Git will significantly enhance your ability to manage and collaborate on projects effectively.