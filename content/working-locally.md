

At 4Geeks, you will be working on many coding projects simultaneously; if you don't organize yourself, it can become a mess pretty quickly. **Don't be the type of person who has to wait until you lose the project code to learn your lesson.** A well-structured workflow and setup will help you:

- Never lose your project code again.
- Reduces the time spent on setup and configuration.
- Makes it easier to switch between projects.
- Ensures your projects are portable and easily shared or moved.
- Helps in avoiding conflicts and errors, especially when working with multiple dependencies.

In this lesson, we will discuss the best practices for setting up your local development environment on any operating system (Windows, Mac, and Linux computers).

## **Consistent Directory Structure**: 

Use a consistent directory structure to organize your projects. This makes it easier to navigate and manage your code. Recommended directories:
 - **Windows**: `C:\Users\<YourUsername>\MyDocuments\Code`
 - **Mac**: `/Users/<YourUsername>/Documents/Code`
 - **Linux**: `/home/<YourUsername>/Documents/Code`

Setting Up Directories:

```windows
 - Navigate to `C:\Users\<YourUsername>\MyDocuments` and create a folder named `Code`.
 - This can be done via File Explorer or using the command line: `$ mkdir C:\Users\<YourUsername>\MyDocuments\Code`
```

## Version Control:
 - Use Git and GitHub for version control. Initialize a Git repository in your project directory using `git init`.
 - Regularly commit your changes with meaningful commit messages.

## Environment Management:
 - Use virtual environments to manage dependencies and avoid conflicts. For Python projects, tools like `venv` or `pipenv` are recommended.
 - Store environment-specific variables in a `.env` file and use a tool like `dotenv` to load them.

## Editor and IDE Configuration:
 - Use a code editor or IDE that supports your language and offers features like linting, debugging, and autocomplete. VSCode is a popular choice across all platforms.
 - Customize your editor settings to match your workflow and team conventions.

## Platform-Specific Instructions

### Windows
1. **Setting Up Directories**:
   - Navigate to `C:\Users\<YourUsername>\MyDocuments` and create a folder named `Code`.
   - This can be done via File Explorer or using the command line:
     ```sh
     mkdir C:\Users\<YourUsername>\MyDocuments\Code
     ```

2. **Git and Environment Management**:
   - Install Git from [git-scm.com](https://git-scm.com/download/win) and configure your user settings:
     ```sh
     git config --global user.name "Your Name"
     git config --global user.email "you@example.com"
     ```
   - Install Python from [python.org](https://www.python.org/downloads/windows/) and use `pipenv` or `venv` for virtual environments.

#### Mac
1. **Setting Up Directories**:
   - Open Terminal and create the `Code` directory:
     ```sh
     mkdir -p ~/Documents/Code
     ```

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
1. **Setting Up Directories**:
   - Open your terminal and create the `Code` directory:
     ```sh
     mkdir -p ~/Documents/Code
     ```

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
