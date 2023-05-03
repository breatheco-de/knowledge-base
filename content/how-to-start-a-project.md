# How to start a coding project

At 4Geeks we understand that starting a project is one of the hardest things to do. There are many ways to start coding a new project, so many that it is tough to know the best or the "recommended way". 

After a lot of hard work, we came up with the following alternatives; please read carefully and choose the best that fits your needs:

## 1) What Github repository are you trying to open?

The most critical step is recognizing which repository you want to open; there are two options:
- Some projects require starting from scratch by using one of 4Geeks' templates.
- Other projects come with pre-written code; you need to fork and clone the project's main repository before opening it.

Ensure you understand the URL of the repository you need to open.

## 2) The repository is a template? (only for templates)

Once you know precisely the repository you need to open, navigate to that repository, and keep in mind the process will be a little different if the repository is a template. If your repository is not a template, move to `step 3`.

Some repositories are meant to be re-used every time you start a new project, at 4Geeks we have created several templates for HTML/CSS, React, Python, etc. [Here is the full list](https://github.com/4GeeksAcademy/Templates-Boilerplates). 

You can tell if the repository is a template because it contains a button to `Use this template`.

![](https://raw.githubusercontent.com/breatheco-de/knowledge-base/main/images/template.png)

If the repository is a template, you will start by creating a new repository based on the template. Click on the button that says `Use this template`; a dropdown menu will be displayed. You have to click the option that says `Create a new repository`: 

![image](https://user-images.githubusercontent.com/109599459/230989999-aeba16c4-c1c1-460a-b1bb-94631de6ccc4.png)

You'll be redirected to a new view where you'll create your new repository. Click the `Select an owner` button; a dropdown menu will be displayed. 

> ⚠️ Important: If you are currently part of the 4Geeks Academy coding bootcamp, make sure to select it on this dropdown, otherwise you will not get free hours of Github Codespaces. 

You have to give your repository a name: We strongly recommend prepending your Github username followed by the name of the project you'll be working on. For example `githubusername-my-project-name`:

![image](https://user-images.githubusercontent.com/109599459/230991453-38566874-f844-4027-9e7d-3662c7548c66.png)

Make sure you select the `public` option, and after that click the `Create repository from template` button:

![image](https://user-images.githubusercontent.com/109599459/230991967-9c08afca-1355-41a5-8a12-0464b98d7bbd.png)

You'll be redirected to the repository URL. The first thing you need to do is to star the repository, so you'll be able to find it easier. You have to click the `Star` button:

![image](https://user-images.githubusercontent.com/109599459/230993816-8f404028-b109-40d5-a47c-e149ae6c17ae.png)

> 👉 Note: You can see your starred repositories by clicking on your profile button (where your picture or avatar is): a dropdown menu will be displayed, and you have to click the `Your stars` option.

![image](https://user-images.githubusercontent.com/109599459/230994342-567b1526-c1fb-4d05-b108-f6f3ec4d4208.png)

## 3) Open the repository

There are 3 ways you can open a repository, please choose only one:

- Using a cloud computer on Codespaces (recommended).
- Using a cloud computer on Gitpod.
- Working on your local machine.

### If you are using Codespaces (takes 10 seconds)

Currently, this is the recommended way to open the repo.

Then, you'll click the `<> Code` green button, and after that, the `Create codespace on main` button:
![image](https://user-images.githubusercontent.com/109599459/230995122-1c00d010-b6d4-4810-852e-1e1524797a34.png)

A new tab will be opened with your codespace ready for work! Start coding!

> 💻 Note: here are more details about [opening repositories with Codespaces](https://4geeks.com/lesson/how-to-use-github-codespaces).

### If you are using Gitpod (for legacy users)

Please download the Gitpod extension [for Chrome](https://chrome.google.com/webstore/detail/gitpod-always-ready-to-co/dodmmooeoklaejobgleioelladacbeki) or [for Firefox](https://addons.mozilla.org/en-US/firefox/addon/gitpod/).

Once you navigate to the repository page, you will find a green button that says `Gitpod`, here is [a screenshot that shows how the button should display on the repository](https://storage.googleapis.com/breathecode-asset-images/15d7c805161244a5a38d7bbf82fb8d355073ad7ac195088a453fba5777c3ef99.png). Press the button and the project will start opening immediately.

> 🍊 Note: here are more details about [opening repositories with Gitpod](https://4geeks.com/lesson/how-to-use-gitpod).

### If you are working locally on your computer

We don't recommend working on your local computer, but here are the instructions if you insist. 

You can find very detailed explanations [in this article](https://4geeks.com/how-to/github-clone-repository), but here is a summary:

- Make sure you have git installed.
- Find your computer terminal or PowerShell (for Windows).
- Navigate to the folder you want to download the files using the `cd` command.
- Run the following command that will download the code:

```sh
$ git clone https://github.com/4GeeksAcademy/html-hello
```

- Once the project has finished downloading, you can open the VSCode editor in that folder, usually by typing `$ code .` on your terminal (notice the dot `.` at the end). If that command does not work, you can still open VSCode, click on "open folder" and find your project folder.

