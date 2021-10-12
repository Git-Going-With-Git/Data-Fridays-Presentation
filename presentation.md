---
marp: true

title: Git Going With Git
description: Git overview presentation for Data Fridays

theme: gaia
_class: lead
backgroundImage: url("docs/hero-background.jpg")
---

# **Git Going With Git**

![bg left:40% 80%](docs/git-logo.png)

Git overview presentation for Data Fridays

https://gitgoingwithgit.com/

* Data Friday
* October 15, 2021

---

<!--
header: "Git Going With Git"
footer: "Data Fridays, UTRGV SMSS"
paginate: true
-->

## **What is Git?**

Git is a version control system for files of any type.

Clone the repository for this presentation:

```sh
git clone https://github.com/Git-Going-With-Git/Data-Fridays-Presentation
```

---

## Terminology

* repository
* commit

---

## Markdown

```markdown
# Git Going With Git

## Overview

* point 1
* point 2
* point 3

## Resources

* resource 1
* resource 2
* resource 3
```

---

## Configuration

On first use, git should be configured.

Your local git installation should also be configured to authenticate
to a remote such as GitHub. This requires the creation of a GitHub *personal access token*.

---

### Local Configuration

After installing git, we must set our name and email:

```sh
git config --global user.name "SpongeBob Squarepants"
git config --global user.email "spongebob@squarepants.com"
```

Verify this was saved by listing the global configuration:

```
git config -l
```

---

### GitHub Configuring

To `clone` a repository or `pull` changes from GitHub, you must authenticate first. In GitHub, go to *settings* and

1. choose *Developer settings*
1. choose *Personal access tokens*
1. *Generate new token* and choose name (ie *Laptop*)
1. choose an *expiration*
1. copy the generated token. It will **not** be available again.

---

### Connect git to GitHub

The first time `clone`ing a project from GitHub, you will be prompted for a *username* and a *password*. This is misleading as GitHub now requires the personal access token to be used as the password.

Clone this presentation's repository with

```sh
git clone https://github.com/Git-Going-With-Git/Data-Fridays-Presentation
```

and enter your *personal access token* when prompted for password.

---

<!--
_class: twocols
style: |
    section.twocols {
        columns: 2;
    }
-->

## Resources

**Interactive Learning**

- [Learn Git Branching](https://learngitbranching.js.org/)
- [Git Kata](https://www.katacoda.com/courses/git)
- [GitHub Learning](https://lab.github.com/)

**Books**

- [Pro Git](https://git-scm.com/book/en/v2)

**Cheat Sheets**

- [Interactive Cheat Sheet](https://ndpsoftware.com/git-cheatsheet.html#loc=index;)
- [GitHub Git Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)

**General**

- [GitLab Training](https://about.gitlab.com/learn/)
- [Official Documentation](https://git-scm.com/doc)
- [Command list](https://git-scm.com/docs)
- [Compilation of Tutorials](https://git-scm.com/doc/ext)
