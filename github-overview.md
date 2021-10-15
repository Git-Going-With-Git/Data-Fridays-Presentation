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

---

# Why is GitHub useful?

---

# Terminology

---

# A Short Demo

---


# Git Remotes

Git remotes are basically "hosted git" external to one's own computer. They facilitate collaborating with others.

Some popular ones include:

* GitHub
* GitLab
* BitBucket

**Note:** Using *markdown* together with git is common and encouraged.

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

# Integrations With 3rd Party Apps

GitHub is an example of a web application that works with git.

Other such applications include Overleaf.

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
