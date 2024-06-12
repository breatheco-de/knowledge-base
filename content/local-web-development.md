---
title: "Local Web Development Setup And Best Practices"
description: "How to start and setup your local web development environment across Windows, Mac, and Linux. Optimize your coding workflow: Project organization, Version control, IDE configuration, etc."
tags: ["javascript", "node", "python", "nvm", "pyenv", "git"]
authors: ["alesanchezr"]

---

As a developer, you will work on many coding projects simultaneously; it can quickly become a mess if you don't organize yourself. **Don't be the person who has to wait until you lose the project code to learn your lesson.** A well-structured workflow and setup will help you:

- Never lose your project code (it happens a lot).
- Reduce the time spent on setup and configuration.
- Easily switch between projects.
- Ensures your projects are portable and easily shared or moved.
- Helps avoid conflicts and errors, especially when working with multiple dependencies.

This lesson will discuss the best practices for setting up your local development environment and workflow on any operating system (Windows, Mac, and Linux computers).

## 1) Create one local directory as the root of all your projects

Use a **consistent directory structure** to organize your projects. This makes switching between projects and navigating and managing your code easier. The following are the recommended directories to save your projects and code:

 - **Windows**: `C:\Users\<YourUsername>\MyDocuments\Code`
 - **Mac**: `/Users/<YourUsername>/Documents/Code`
 - **Linux**: `/home/<YourUsername>/Documents/Code`

The following steps will guide you on how to create this root directory depending on your operating system:

```windows runable=true
 - Navigate to `C:\Users\<YourUsername>\MyDocuments` and create a folder named `Code`.

This folder can be created via File Explorer or using the following command `mkdir C:\Users\<YourUsername>\MyDocuments\Code`
```
```macos
Open Terminal and create the `Code` directory using the following command: `$ mkdir -p ~/Documents/Code`
```
```linux
Open your terminal and create the `Code` directory using the following command: `$ mkdir -p ~/Documents/Code`
```

## 2) Each project must be a new folder and git repository

You cannot work and/or collaborate on multiple projects without using a version control system like [Git](https://4geeks.com/technology/git) and [Github](https://4geeks.com/technology/github).

Every time you start working on a project, you will make changes to the files and those updates will be recorded and tracked by git:

- You will never lose a single file or file change ever again.
- You will be able to go back in time as you please.
- Other developers will be able to see and understand your latest changes in a matter of seconds.

### Steps to start tracking file versions

- Open an account on Github.com and learn the basics on [how to use GitHub](/lesson/welcome-to-github).
- Make sure to [install git on your Windows, MacOS or Linux computer](/how-to/install-git-on-windows-macos-and-linux).
- Initialize a separate Git repository for every project directory: This step will be done later as you start working on projects by [cloning a current repository](https://4geeks.com/how-to/github-clone-repository) or creating a new one.
 - Regularly commit your changes with meaningful commit messages.

## 3) Each project must be a have different environment

An "environment" refers to the setup or configuration under which a project runs. Ideally, you have one environment for one project, which means you will have as many environments as projects.

### Why have different environments?

There are several reasons; let's focus on one: **programming language Versions**.
Technology evolves too fast: If you start a project in `Node v12` it will become obsolete after a few months.
To avoid errors, you must `freeze in time` all the project dependencies (libraries, programing language version, etc.).

> 📝 Learn more about [creating environments in programming](/lesson/what-is-an-environment-in-programming#what-are-environment-variables)

Another reason is **privacy and security** when integrating with other APIs.
For example, you need to use API credentials (API Keys) to make an API call to the TikTok API.
If these credentials are typed directly into your code, they are exposed to the public, and anyone can use the TikTok API on your behalf.
To avoid security incidents, you have to use environment variables.

> 📝 Learn more about [environment variables in programming](/lesson/what-is-an-environment-in-programming#what-are-environment-variables)

### Using a .env file for environment variables

Once you have your environment ready, it is standard to create a file called `.env` that will not be uploaded to Github because it will be ignored by Git (the version control system).

## 4) Use VSCode as your default IDE (coding editor):

- [Download VSCode](https://code.visualstudio.com/download)'s and install its latest version from the official website.
- VSCode supports almost any programming language and offers features like linting and autocomplete that will prevent hundreds of bugs per day and make you code super fast (eventually 🤣).
- VSCode is a popular that is probably used at your potential employer companies.
- Customize your editor settings to match your workflow and team conventions.

## Install your programming languages

These instructions vary depending on the programming language you choose to install; our recommendation is to have at least Node and Python, so here are the instructions for both languages.

We strongly recommend installing node and python using a vier

### Install Python using Pyenv

Pyenv is a tool for managing different versions of Python on our computer. It makes it easy to switch between versions as needed for the environment we are developing in. Click here to learn [how to install PyEnv on your local computer](https://4geeks.com/how-to/what-is-pyenv-and-how-to-install-pyenv).

### Install Node using NVM

NVM (node version manager) allows you to manage multiple Javascript projects and Node.js environments and switch between them depending on the project's needs. Click here to learn [how to install NVM on every operating system](https://4geeks.com/how-to/install-nvm-on-every-operating-system).

## Additional Tips for Local Web Development

- **Backup**: Regularly back up your code to an external drive or a cloud service like GitHub, GitLab, or Bitbucket.
- **Documentation**: Maintain good documentation within your projects to help others (and your future self) understand the code.
- **Collaboration**: Use tools like GitHub or GitLab for collaborative development, including pull requests and code reviews.

By following these best practices, students will be able to create a robust and organized local development environment that supports efficient and effective coding.
