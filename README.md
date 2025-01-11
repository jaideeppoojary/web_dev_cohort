# Welcome Devs! Your Git & GitHub Guide

Hello and welcome!  This document is your guide to using Git and GitHub effectively at ChaiCode. Whether you're a beginner or have some experience, this guide will help you understand how we work with Git and GitHub for version control and team collaboration. By the end of this guide, you'll be comfortable using Git and GitHub for your day-to-day work.

# Why git ?
Have you ever wondered how so many developers' code is managed or how changes are rolled back when something goes wrong? That's where Git comes in! Git helps developers collaborate, track changes, and keep everything running smoothly.

But here's an interesting question - Is Git really necessary? Absolutely! Without Git, managing code changes and collaborating in a team would be chaotic.

You might ask, Why is Git required? Well in simple, Git makes it easy to track every change made to the code, allowing teams to work together without overwriting each other's work.

> GitHub is a platform where you can store and share your Git repositories. It helps teams work together on projects. You can see each other's changes, leave comments, and suggest improvements.


Ok, let's start…🔥

# Installation
* Visit git official website: Git - Downloads
If you are on windows, it's just simply clicking download and click next, next, next.

* If you are using macOS. You can run below command.

  ```
  brew install git
  ```

* If you are using linux. You can run below command.
  ```
  sudo apt install git
  ```

# Configuring Git
Once Git is installed, you need to set up your name and email. Open your terminal and run the following commands.
  ```
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```

For now, only this much is enough. [You can check more](https://docs.github.com/en/get-started/getting-started-with-git).

___

# Getting started with your GitHub account
Creating the github account is simple. To sign up for an account, navigate to https://github.com/ and follow the prompts.

* It asks general question like username and password enter and proceed further.
* Clear the I'm not a robot step.
* After that your account is ready to use.

___
# Setting up the shared project in local machine using git & GitHub
* Cloning Repository include following steps

* Copy the shared git repository (project) URL. 
* Open the terminal in your local machine.
* Run the below command.

  ```
  git clone https://github.com/ChaiCode/example-repo.git
  ```

* After cloning, go into the project folder

# Setting up the shared project in local machine using git & GitHub
1. Cloning Repository include following steps

* Copy the shared git repository (project) URL. 
* Open the terminal in your local machine.
* Run the below command.

  ```
  git clone https://github.com/ChaiCode/example-repo.git
  ```

* After cloning, go into the project folder

# Basic Git Commands
Let's see about some basic commands. That you will be using while working on a project.

> When you are working on project and made changes in many files. You can use this below command to check what, and all files are newly added or modified.

* `git status` – Check the status of your files (modified, added, etc.)

> Git will not track the changes unless you instruct it. You can do it by using below command.
 * `git add .` – Add all the changes you made to be saved (commit).

> After telling the git what and all the files to track using above command use can use the below command to save your changes.

* `git commit -m "Your message"` – Save your changes with a message.

> After saving the changes using the above command. These changes will be in your local. You can use the below command to push the changes to GitHub, So other take the updates changes.
 * `git push` – Push your changes to GitHub.

> Suppose the updated changes are in Remote branch (GitHub). You can get those updated changes using the below command.
* `git pull` – Get the latest changes from the GitHub repository.

> You can use the below command to check all the commit history (saved changes).
* `git log` – View a history of your commits.

___

# Commit Message Rules
While saving the changes using the git commit command you should follow rules. So that while see the commit history it should be easily untestable by others.

When writing commit messages, follow these simple rules:

1. **Use present tense**: Write "Add feature" instead of "Added feature".
2. **Capitalize the first letter** of the message.
3. **Keep it short and to the point** (50 characters or less).
4. **Use prefixes for categorization**, such as:

* `feat`: for new features
* `fix`: for bug fixes
* `chore`: for general updates
* `docs`: for documentation updates

### Example commit messages:
```
  feat: Add tea selection feature
  fix: Resolve login issue for tea lovers
  docs: Update README with chai varieties
```