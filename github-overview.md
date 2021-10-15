---
marp: true

title: GitHub Overview, Git Going With Git
description: GitHub overview for Data Fridays

theme: gaia
_class: lead
backgroundImage: url("docs/hero-background.jpg")
---

# **Git Going With Git**

![bg left:40% 80%](docs/git-logo.png)

**GitHub** Overview

*GitHub overview for Data Fridays*

https://gitgoingwithgit.com/

- Data Friday
- October 15, 2021

---

<!--
header: "**GitHub Overview**, Git Going With Git"
footer: "Data Fridays, UTRGV SMSS"
paginate: true
-->

# What is GitHub?

GitHub is a hostd version of git that can be used to collaborate with others. It is usually used as the *centralized* git repository.

Besides git, GitHub also has other features commonly used when collaborating in projects:

- issue management
- discussions
- project management
- wiki

---

# Why is GitHub useful?

GitHub is the leading platform for *open source projects*, as it facilitates working in projects with a team.

- code (or any files, really) lives in the cloud, so you can access your files from anywhere
- central place to manage project
- easy to share work with others
- integrations to other commonly used platforms
- **FREE** (...mostly free)


---

# Terminology

- public repository / private repository
- issue / pull request
- `README.md` / markdown
- organizations
- GitHub pages
- actions / continuous deployment
- author / contributor / owner
- clone / fork

---

# Git Remotes

Git remotes are basically "hosted git" external to one's own computer. They facilitate collaborating with others.

Some popular ones include:

- GitHub
- GitLab
- BitBucket

**Note:** Using *markdown* together with git is common and encouraged.

---

# A Short Demo 🖱️

Overview of the GitHub user interface

Examples 
- [deepfakes/faceswap](https://github.com/deepfakes/faceswap) repository

---

# GitHub Is Not Magic. Collaboration Is Still (kinda) Hard

- Using GitHub well requires good project management practices and constant management
- Non-git features are rudimentary
- User interface is busy and may be intimidating
- Learning curve (as with git) may be large

---

# GitHub Configuration

Your local git installation should be configured to authenticate
to a remote such as GitHub to be able to `clone` or `pull` from a GitHub repository. In GitHub, go to *settings* and

1. choose *Developer settings*
1. choose *Personal access tokens*
1. *Generate new token* and choose name (ie *Laptop*)
1. choose an *expiration*
1. copy the generated token. It will **not** be available again.

---

## Connect git to GitHub

The first time `clone`ing a project from GitHub, you will be prompted for a *username* and a *password*. This is misleading as GitHub now requires the personal access token to be used as the password.

Clone this presentation's repository with

```sh
git clone https://github.com/Git-Going-With-Git/Data-Fridays-Presentation
```

and enter your *personal access token* when prompted for password.

---

# GitHub Features

- organizations, permissions
- GitHub pages
- issues, pull requests
- wiki
- project management
- actions
- packages

---

## Issues and Pull Requests

When working collaboratively, it becomes very important to have a place to discuss issues (bugs, questions, other problems) that is *close to* where the actual problems live.

GitHub has the concepts of issues, pull requests, discussions, and projects to help with this. 

**DEMO** 🖱️

---

## GitHub Pages

Simple static websites can be hosted on GitHub itself. To host a website on GitHub, the special `gh-page` branch is used. Examples of websites that may be hosted on GitHub pages include:

- documentation
- simple personal website/blog
- R Markdown
- Jupyter Notebooks

**DEMO** [https://datafriday.gitgoingwithgit.com/](https://datafriday.gitgoingwithgit.com/)

---

# Git Clients

- Command line 🖱️
- GitKraken 🖱️

---

# Integration With IDEs

Many popular IDEs (integrated development environments) have native git integration.

- RStudio 🖱️ - [Example R Studio Repository](https://github.com/rmercadojr/Statistical-Learning---Case-Study-1)
- VS Code 🖱️ - [Presentation Example](https://github.com/Git-Going-With-Git/Data-Fridays-Presentation)
- JetBrains' IDEs

---

# Integration With 3rd Party Apps

There are many third party applications integrate very well with GitHub. Here's a short list of such applications:

- Overleaf 🖱️ - [Overleaf Example](https://www.overleaf.com/project/615282411e6ff12dfd3ca7be), [Repository Example](https://github.com/rmercadojr/MATH-8371---Homework-02)
- Replit 🖱️ - [replit example](https://github.com/rmercadojr/ExamplePythonRepl/tree/master)
- Diagrams dot Net 🖱️ - [ExampleDiagram.drawio Example](https://github.com/Git-Going-With-Git/Data-Fridays-Presentation/tree/main/examples)
- CoCalc - has GitHub integration but requires paid subscription
- Jira, Monday, ClickUp
- Slack, Teams - useful for notifications

---

<!--
_class: twocols
style: |
    section.twocols {
        columns: 2;
    }
-->

# Resources

**Interactive Learning**

- [Learn Git Branching](https://learngitbranching.js.org/)
- [Git Kata](https://www.katacoda.com/courses/git)
- [GitHub Learning](https://lab.github.com/)

**Books**

- [Pro Git](https://git-scm.com/book/en/v2)

**Cheat Sheets**

- [Interactive Cheat Sheet](https://ndpsoftware.com/git-cheatsheet.html#loc=index;)
- [GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
- [GitHub Git Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)

**General**

- [GitLab Training](https://about.gitlab.com/learn/)
- [Official Documentation](https://git-scm.com/doc)
- [Command list](https://git-scm.com/docs)
- [Compilation of Tutorials](https://git-scm.com/doc/ext)
