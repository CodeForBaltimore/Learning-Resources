# Learning Git

Git is a software version control system that was created by Linus Torvalds, the creator of the Linux kernel.  Git can track changes in any text based files and record adding and deleting of binary based files.  Because of Git's ease of use and versatility, today it is used to track much more than source code.  One of the best ways to learn git, is to use git with every project.  

You begin tracking a project by initializing a repository (commonly referred to as a repo) in the root directory of a project.  The following shows a simple example of creating a sample project and initializing a Git repository.

```
mkdir sample_project
cd sample_project
echo "# Sample Project Readme" > README.md
git init
git add README.md
git commit -m "initial commit"
```

## Installing Git

Installing Git on any system is fairly straight forward.  You can use your package manager or directly download and install from the Git website

### MacOS

#### Direct Download

Visit the [Downloads](https://git-scm.com/downloads) page of the Git website to download the install dmg file.

#### Brew Install

From the command line in Terminal:

```
brew install git
```

### Windows

#### Direct Download

Visit the [Downloads](https://git-scm.com/downloads) page of the Git website to download the install exe file.

#### Chocolatey Install

From the command line in CMD or PowerShell:

```
C:\> choco install git
```

### Linux

Visit the [Download for Linux and Unix](https://git-scm.com/download/linux) page for instructions for your distribution.  

## Getting Started Using Git

Git has many online resources to get you starting using Git for your projects.  Again, the best way to learn Git, is to use it with every project.  The following resources will get you started using Git:

### [Node School](https://nodeschool.io)

One of the best beginner resources on the web to get started with Javascript & Node programming, but provides other courses that support tooling like Git.  Look for the git-it course to get started.

### [Learn Git Branching](https://learngitbranching.js.org/)

An online interactive site that teaches you Git commands and also gives you an environment to try what you are learning.

### [Git Documentation](https://git-scm.com/doc)

Git provides step-by-step instructions on getting up and running with Git as well as their own instructional videos.

### [YouTube](https://www.youtube.com/results?search_query=git)

YouTube has a ton of videos on Git.  Git does not change much so your don't have to worry about watching a video a year or two old.  Git does operate differently between MacOS/Linux and Windows though.  Be sure to look for Windows specific Git videos when searching.

## Git Online 

Git repos are stored locally on your computer.  As a way to access them remotely or to easily move between computers, there are many online repo sites.  The most common are:

### [GitHub](https://github.com)

GitHub is arguably the most widely used online repo and supports free public repos.  Private repos are reserved for pay accounts.  GitHub is simple and fast.

### [GitLab](https://about.gitlab.com/)

GitLab offers both public and private online repos for free.  Also GitLab has rolled out AutoDevOps which handles a lot of the deployment processes for you.  GitLab is well known for companies hosting their own GitLab installations.

### [BitBucket](https://bitbucket.org/)

BitBucket offers most of the same features as GitLab with free public and private repos and integrated Continuous Deployment.  BitBucket, being owned by Atlassian, integrates great with Trello and Jira.

## Other Resources

### Graphical User Interface (GUI) Git

Learning Git on the command line is the best way to grasp the concepts.  Once you have a solid understanding, you may wish to use a graphical program to work with Git.  There are several GUI Git applications on the [Git GUI Clients](https://git-scm.com/downloads/guis) page.  Some of the more popular options are:

* [GitKraken](https://www.gitkraken.com/)
* [Tower](https://www.git-tower.com/)
* [git-cola](https://git-cola.github.io/)
* [Github Desktop](https://desktop.github.com/)

### Git Integration with Code/Text Editors

Now most code/text editors come with Git integration built in.  If your plan is to use Git graphically, then you should factor that integration into your choice of code/text editor and possibly skip one of the clients above.

### Github Command Line Interface (CLI)

Some may prefer to stay in the command line all the time.  GitHub, GitLab, and BitBucket all have command line interfaces.  Their functionality is not the same between all three, but the links below will give you more information.

* [Hub for GitHub](https://hub.github.com/)
* [Lab for GitLab](https://www.npmjs.com/package/git-lab-cli)
* [BB for BitBucket](https://bitbucket.org/zhemao/bitbucket-cli)

### Git Terminal Shell Integration

Git integration into the Terminal Shell provides command line information when you are currently inside a git repo.  Information like the branch name, repo status, uncommited changes, and more are displayed on the command line prompt so you dont have to type `git status` every time.  These integrations are provided for bash, zsh, fish, and PowerShell.  The most common in the MacOS/Linux realm is Robby Russell's [Oh-My-ZSH](https://github.com/robbyrussell/oh-my-zsh).  Windows users are probably familiar with [Posh-git](https://github.com/dahlbyk/posh-git)