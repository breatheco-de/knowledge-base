---
title: "Local Web Development Setup And Best Practices"
description: "How to start and setup your local web development environment across Windows, Mac, and Linux. Optimize your coding workflow: Project organization, Version control, IDE configuration, etc."
tags: ["javascript", "node", "python", "nvm", "pyenv", "git"]
authors: ["alesanchezr"]

---

At 4Geeks, you will be working on many coding projects simultaneously; if you don't organize yourself, it can quickly become a mess. **Don't be the person who has to wait until you lose the project code to learn your lesson.** A well-structured workflow and setup will help you:

- Never lose your project code (it happens a lot).
- Reduce the time spent on setup and configuration.
- Easily switch between projects.
- Ensures your projects are portable and easily shared or moved.
- Helps avoid conflicts and errors, especially when working with multiple dependencies.

This lesson will discuss the best practices for setting up your local development environment and workflow on any operating system (Windows, Mac, and Linux computers).

## **Consistent Directory Structure**: 

Use a consistent directory structure to organize your projects. This makes switching between projects and navigating and managing your code easier. The following are the recommended directories to save your projects and code:

 - **Windows**: `C:\Users\<YourUsername>\MyDocuments\Code`
 - **Mac**: `/Users/<YourUsername>/Documents/Code`
 - **Linux**: `/home/<YourUsername>/Documents/Code`

### Creating your project code directory:

```windows
 - Navigate to `C:\Users\<YourUsername>\MyDocuments` and create a folder named `Code`.
 - This can be done via File Explorer or using [the command line](https://4geeks.com/lesson/the-command-line-the-terminal): `$ mkdir C:\Users\<YourUsername>\MyDocuments\Code`
```
```macos
Open Terminal and create the `Code` directory: `$ mkdir -p ~/Documents/Code`
```
```linux
Open your terminal and create the `Code` directory: `$ mkdir -p ~/Documents/Code`
```

## Version Control

We strongly recommend you use [Git](https://4geeks.com/technology/git) and [Github](https://4geeks.com/technology/github) to manage your project files.

- Make sure to [install git on your Windows, MacOS or Linux computer](/how-to/install-git-on-windows-macos-and-linux).
- Initialize a Git repository separate for every project directory, this will be done later, by [cloning a current repository](https://4geeks.com/how-to/github-clone-repository) or creating a new one.
 - Regularly commit your changes with meaningful commit messages.

## Environment Management:

We strongly recommend using virtual environments for every project you build, to manage dependencies and avoid conflicts. For Python projects, tools like `venv` or `pipenv` are recommended.
 - Store environment-specific variables in a `.env` file and use a tool like `dotenv` to load them.

## Editor and IDE Configuration:
 - Use a code editor or IDE that supports your language and offers features like linting, debugging, and autocomplete. VSCode is a popular choice across all platforms.
 - Customize your editor settings to match your workflow and team conventions.

## Platform-Specific Instructions

### Windows
     ```

2. **Git and Environment Management**:
   - Install Git from [git-scm.com](https://git-scm.com/download/win) and configure your user settings:
     ```sh
     git config --global user.name "Your Name"
     git config --global user.email "you@example.com"
     ```
   - Install Python from [python.org](https://www.python.org/downloads/windows/) and use `pipenv` or `venv` for virtual environments.

#### Mac

2. **Git and Environment Management**:
   - Install Git using Homebrew:
     ```sh
     brew install git
     ```
   - Set up Git user settings as mentioned above.
   - Install Python and virtual environments:
     ```sh
     brew install python
     ```

#### Linux

2. **Git and Environment Management**:
   - Install Git using your package manager (e.g., `apt` for Ubuntu):
     ```sh
     sudo apt-get install git
     ```
   - Set up Git user settings as mentioned above.
   - Install Python and virtual environments:
     ```sh
     sudo apt-get install python3 python3-venv
     ```

### Additional Tips

- **Backup**: Regularly back up your code to an external drive or a cloud service like GitHub, GitLab, or Bitbucket.
- **Documentation**: Maintain good documentation within your projects to help others (and your future self) understand the code.
- **Collaboration**: Use tools like GitHub or GitLab for collaborative development, including pull requests and code reviews.

By following these best practices, students will be able to create a robust and organized local development environment that supports efficient and effective coding.
