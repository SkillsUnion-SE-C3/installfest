[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Installfest

# Windows with WSL

## Command line terminal

You're going to need to do a few things before you can get started. Watch [this video](https://www.youtube.com/watch?v=-atblwgc63E) till the 3:25 marker or read the instructions in [this article](https://docs.microsoft.com/en-us/windows/wsl/install-win10#manual-installation-steps) to set up the latest Ubuntu Linux subsystem on Windows 10 for you.

## Managing packages - APT(Advanced Package Tool)

https://codeburst.io/a-beginners-guide-to-using-apt-get-commands-in-linux-ubuntu-d5f102a56fc4

## Git

As difficult as it can be to track all the changes you've made in your code, it is even more so when working in a team. That's why developers use Git and GitHub to manage code changes. Our code is our livelihood so it's important that we safely and frequently store our work. This allows us to go back to a point when our app was last working if we make a feature that ends up breaking our app.

You don't need to master Git right away. We will talk about it in an upcoming session.

1. [Download and install the latest version of Git](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-git#installing-git)
2. Once the installation is finished and you can see your username followed by a dollar sign in the last line of the terminal
   - run `git --version` in your terminal
   - You should see `git version` followed by a version number in your terminal
3. [Set up git config in your wsl terminal](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-git#git-config-file-setup)
   - Use the same email you signed up to GitHub with.
4. [Connect GitHub with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
5. [Go to SSH settings page in github and add the key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
6. [Test if ssh has been correctly set up](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection)

## Text editor: Visual Studio Code

During this course, we're going to be using Visual Studio Code. It's a free and extensible code-editor that will serve you well for a long time.

1. [Follow the instructions to install and set up VSC](https://code.visualstudio.com/docs/remote/wsl) until "FROM THE WINDOWS COMMAND PROMPT" section.

## Postman

[Postman from the website](https://www.postman.com/)

## NodeJS

1. Install nvm - Run these three lines in your wsl terminal
`curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash`
`source ~/.profile`
`nvm install --lts`

## Python

1. In your wsl terminal run:
`python3 --version` This should return your Python version number. If you need to update your version of Python
2. Install pip
- `sudo apt install python3-pip`

-------------

# Mac

## Command line terminal

You already have a working command-line environment you can use.

Open spotlight search (default way to do this is by hitting command and the space bar) and type in “terminal”. Select the application called terminal and press the return key. This should open up an app with a black background. When you see your username followed by a dollar sign, you’re ready to start using command line.

## Managing packages - Brew

1. Install [Homebrew](https://brew.sh/) onto your system by pasting the provided command into your terminal.
2. Once the installation is finished and you can see your username followed by a dollar sign in the last line of the terminal
   - type `brew -v` into your terminal
   - You should see the word Homebrew with a version number in your terminal.

## Git

As difficult as it can be to track all the changes you've made in your code, it is even more so when working in a team. That's why developers use Git and GitHub to manage code changes. Our code is our livelihood so it's important that we safely and frequently store our work. This allows us to go back to a point when our app was last working if we make a feature that ends up breaking our app.

You don't need to master Git right away. We will talk about it in an upcoming session.

1. [Get git using Brew](https://git-scm.com/download/mac)
2. Once the installation is finished and you can see your username followed by a dollar sign in the last line of the terminal
   - type `git --version` into your terminal
   - You should see `git version` followed by a version number in your terminal
3. Configure git to your username and email
   - run `git config --global user.name "Your Name"`
   - run `git config --global user.email "your@email.com"` (same one you used to sign up to GitHub)
4. [Connect GitHub with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
5. [Go to SSH settings page in github and add the key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
6. [Test if ssh has been correctly set up](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection)


## Text editor: Visual Studio Code

During this course, we're going to be using Visual Studio Code. It's a free and extensible code-editor that will serve you well for a long time.

1. [Download VSC](https://code.visualstudio.com/)
2. You must first run a command (**Shell Command: Install 'code' command in PATH**) to add VS Code executable to the `PATH` environment variable. Read the [macOS setup guide](https://code.visualstudio.com/docs/setup/mac) for help.

## Postman

[Postman from the website](https://www.postman.com/)

## NodeJS

Install node using brew: Run the command below in your terminal
`brew install node`

## Python

Install python 3 using brew: Run the command below in your terminal
`brew install python`
