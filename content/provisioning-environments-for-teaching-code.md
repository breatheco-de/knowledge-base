---
title: "Provisioning Environments for Teaching Coding-Related Skills"
subtitle: "Learn how to effortlessly provision containers, leverage template repositories, and dive into hands-on coding experiences."
tags: ["4geeks", "learn-to-code"]
authors: ["alesanchezr"]
---

Setting up the initial project codebase is one of the biggest obstacles to code. Junior -and sometimes even senior- struggles to configure all the tools, templates, languages, and environments needed to start coding. There is also an overwhelming amount of template starters and very different trends or schools of thought how best practices. For this and other reasons 4Geeks has, since day one, made a considerable effort to develop the tools needed to remove this friction from learners.

In this article, we will explain in detail 4Geeks.com proposal for provisioning coding-related environments for learning.

## When to provision

We must immediately provide a new coding environment for students whenever they start or continue working on a project or exercise. These coding environments are a combination of two main things:
The container: the computer.
The template repository: the initial files.
Learnpack: Interactive tutorial engine.

### The container

Think of the container like a computer with everything the student needs to code: The languages already installed, the servers and databases, VSCode editor, plugins, etc. We work with GitHub Codespaces or Gitpod as container providers, but both use Kubernetes and Docker to orchestrate the student computers.

We don't require using the academy's coding containers but strongly recommend it. But, of course, students can always use their local computers instead.

### The Template Repository

We put great effort into creating and maintaining initial files and templates to start working on every technology we teach. We prioritize ease of use and best practices. Every template comes with a README.md file that helps you quickly start coding, one video explaining how to use it, and a complimentary link for [thorough documentation](https://start.4geeksacademy.com).

Here's a list of each technology's [most common repository templates](https://github.com/4GeeksAcademy/Templates-Boilerplates).

## Starting a new project

We aim to provide students with explicit instructions on starting each coding project. Here is one example:

![how o start a coding project in 4geeks](https://github.com/breatheco-de/knowledge-base/blob/main/images/how-to-start-project.png?raw=true)
Note: These instructions are subject to changes; you may see something different on your 4Geeks account.

Our goal is to provide clear instructions while keeping the process very close to real life; we want to allow students to experience browsing repositories, forking, cloning or any of the typical activities they will need to do when starting a project in a company.

### Starting a new exercise

When starting a new exercise, priorities are different; exercises are isolated environments for practicing particular skills; we want students to jump into exercises immediately without caring about how the exercises were setup.

That is why, instead of giving them the repository URL, we go ahead and start provisioning the cloud computer for them; they only have to decide if they want to "start from scratch" or "continue previous" exercises.

![](https://github.com/breatheco-de/knowledge-base/blob/main/images/open-exercise.png?raw=true)

## Provisioning vendors

We are compatible with the following vendors; click on their names to learn more about them:
[Codespaces by Github](https://4geeks.com/lesson/what-is-github-codespaces).
[Gitpod](https://4geeks.com/lesson/how-to-use-gitpod).
