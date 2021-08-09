[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Installfest

## Prerequisites

Before this session, students should already:

- Update their computer to the latest version of whichever OS they are using

## Learning Objectives

After this session, students should know:

- What are the different pieces of software installed on their systems

After this session, students should be able to:

- Have a system that is setup with all of the required applications they will need for the course
- Be able to use Visual Studio Code

## Instructor Notes

- If you need to, you can use different installation approach for any of the required applications

---

## Opening (5 minutes / 0:05)

### Review current lesson objectives

Today is not about a lesson but more about getting your computers ready for what you will need for the next 3 units. We will cover everything we're installing today in more detail when we start using them down the road. For now, let's focus on getting your computer ready for whats to come.

## Managing Packages

**If you are using a Mac or Linux operating system,** then you already have a working command-line environment you can use.

**If you're using Windows 10,** then you're going to need to do a few things before you can get started. Watch [this video](https://www.youtube.com/watch?v=-atblwgc63E) till the 3:25 marker or read the instructions in [this article](https://docs.microsoft.com/en-us/windows/wsl/install-win10#manual-installation-steps) to set up the latest Ubuntu Linux subsystem on Windows 10 for you.

If you're using MacOS, then make sure you install [Homebrew](https://brew.sh/) on your system.

## Managing your code

As difficult as it can be to track all the changes you've made in your code, it is even more so when working in a team. That's why developers use Git and GitHub to manage code changes. Our code is our livelihood so it's important that we safely and frequently store our work. This allows us to go back to a point when our app was last working if we make a feature that ends up breaking our app.

You don't need to master Git right away. We will talk about it in the next session.

### Setting up Git

1. [Download and install the latest version of Git](https://git-scm.com/downloads)
  
   > Tip: You can use your package manager to install the latest version
2. [Set your username in Git](https://docs.github.com/en/github/using-git/setting-your-username-in-git)
3. [Set your commit email address in Git](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address#setting-your-commit-email-address-in-git)
4. Create an [account on GitHub](http://github.com/) using the same email address
5. [Connecting to GitHub with SSH](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)

   Follow the relevant sections to make sure:
   1. Everyone has a SSH Key on their system
   2. Added to the [GitHub SSH Keys](https://github.com/settings/keys) section
   3. And can successfully [test their SSH connection](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/testing-your-ssh-connection)

## Installing a text editor

During this course, we're going to be using Visual Studio Code. It's a free and extensible code-editor that will serve you well for a long time.

Make sure to [install Visual Studio Code](https://code.visualstudio.com/) on your computer as it supports all the major operating systems. I recommend you read [this article on codecademy](https://www.codecademy.com/articles/visual-studio-code) to get started.

### Launching from command line

You can launch VS Code from the command line to quickly open a file, folder, or project. Typically, you open VS Code within the context of a folder. To do this, from an open terminal or command prompt, navigate to your project folder and type `code .`

Users on **macOS** must first run a command (**Shell Command: Install 'code' command in PATH**) to add VS Code executable to the `PATH` environment variable. Read the [macOS setup guide](https://code.visualstudio.com/docs/setup/mac) for help.

Windows and Linux installations should add the VS Code binaries location to your system path. If this isn't the case, you can manually add the location to the `Path` environment variable (`$PATH` on Linux). For example, on Windows, VS Code is installed under `AppData\Local\Programs\Microsoft VS Code\bin`. To review platform specific setup instructions, see [Setup](https://code.visualstudio.com/docs/setup/setup-overview).

## Installing Postman

Not much to do here, just download the latest version of [Postman from the website](https://www.postman.com/) and you are good to go.

## NodeJS

Make sure to only install the latest **LTS** version of **NodeJS** along with most recent version of **NPM**. You should use the `apt` or `brew` package managers to install the required packages. But in case of issues, use the best possible option available for each OS platform.

## Python

Make sure to only install the latest build for **Python 3** along with most recent version of **pip**. You should use the `apt` or `brew` package managers to install the required packages. But in case of issues, use the best possible option available for each OS platform.

## MongoDB

Make sure to only install the latest version of **MongoDB**. You should use the `apt` or `brew` package managers to install the required packages. But in case of issues, use the best possible option available for each OS platform.

## PostgreSQL

Make sure to only install the latest version of **PostgreSQL**. You should use the `apt` or `brew` package managers to install the required packages. But in case of issues, use the best possible option available for each OS platform.

## Independent Assignment

Assign the following material(s) for students to complete before the next session:

- None

## Optional Topics

- Use your discretion

## Recommended Reading

- Use your discretion

## Additional Resources

- Use your discretion
