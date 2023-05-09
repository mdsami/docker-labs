# Contributing guidelines
**🥳 Welcome to the Docker Labs! 🥳**

We invite everyone who is interested to get involved. Even if you just want to correct a typo, your contribution is very much appreciated! The guidelines below should help you navigate the practical steps to contribute to this project.

**Document content** <br>
*Before contributing* <br>
  * [Before you contribute](#before-you-contribute)
  * [How can I contribute?](#how-can-i-contribute)  

*Contributing*
  * [Joining the discussion](#joining-the-discussion)
  * [Using Issues to contribute practical ideas or bug reports](#using-issues-to-contribute-practical-ideas-or-bug-reports)
    + [How to open an issue?](#how-to-open-an-issue)
  * [Contributing to handbook content](#contributing-to-handbook-content)
    + [1. Fork the repository: Copy the repository to your own account](#1-fork-the-repository-copy-the-repository-to-your-own-account)
    + [2. Edit the content in your own copy (edit, stage, commit)](#2-edit-the-content-in-your-own-copy-edit-stage-commit)
      - [General tips for editing content](#general-tips-for-editing-content)
      - [A. Easiest way: Editing files on GitHub](#a-easiest-way-editing-files-on-github)
      - [B. More advanced way: Editing files locally](#b-more-advanced-way-editing-files-locally)
    + [3. Open a pull request: ask the maintainers to merge your edits](#3-open-a-pull-request-ask-the-maintainers-to-merge-your-edits)  
 
 *After contributing*
  * [Recognition for your contribution](#recognition-for-your-contribution)

---

## Before you contribute
Before you contribute, the following points are important to take into account:
1. Please read through our [Code of Conduct](https://github.com/mdsami/docker-labs/blob/main/CODE_OF_CONDUCT.md) and make sure you familiarize yourself with its contents. We expect all of our contributors to comply with the terms specified there.
2. At the moment, all contributions go through our GitHub repository, https://github.com/mdsami/docker-labs/. In order for you to be able to contribute, you first have to [create a GitHub account](https://github.com/join). **Note, the Dockers Labs on GitHub requires to use [2-factor authentication for your GitHub account](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication)**. <br>
If you want to be able to work on your local PC, you should additionally have [`git`](https://git-scm.com/downloads) installed (the version control software underlying GitHub) and optionally a user interface (e.g., [Rstudio](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN), [GitKraken](https://www.gitkraken.com/download), etc.) that can work with git.
3. Throughout this project, we write in Markdown. This is a way of formatting text to add, for example, numbering, headers, bold text, hyperlinks, etc. to plain text. See [this link](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for some basic syntax to get you started.
4. If you want to contribute content, please take into account the [styleguide](https://github.com/Umdsami/docker-labs/blob/main/styleguide.md).
5. We find it important to credit everyone for their contributions. Head over to the [Contribution recognition section](#3-open-a-pull-request-ask-the-maintainers-to-merge-your-edits) to discover how.

## How can I contribute?
You can contribute to the Data Privacy Docker Labs in the following ways:
- [Joining the discussion](#joining-the-discussion). Examples scenarios:
  - I have a question that's not necessarily related to specific files in the repository or parts of the Docker Labs.
  - I want to share news that's relevant for the Docker Labs.
  - I want to start or participate in an open-ended conversation.
  - I want to make an announcement to my community.
- Coming up with ideas for the docker-compose file or let us know about errors or bugs, by [opening an Issue](#using-issues-to-contribute-practical-ideas-or-bug-reports). Example scenarios:
  - I want to keep track of tasks, enhancements and bugs.
  - I want to file a bug report.
  - I want to share feedback about a specific part of the docker-compose file.
  - I want to ask a question about files in the repository or parts of the Docker Labs.
- [Contributing or editing Docker Labs content](#contributing-to-handbook-content). Example scenarios:
  - I want to fix a typo in the repository or in the Docker Labs.
  - I want to make changes to the repository of to the Docker Labs.
  - I want to make changes to fix an issue.
  - I want to comment on changes suggested by others.

---

## Joining the discussion
Do you want some feedback from others on your idea before you propose it as an Issue? Do you want to discuss some of the content of the Docker Labs with others? Is there news that other contributors should be aware of? Or do you have a question about any part of the project? Then GitHub discussions is a great place to go! 

1. Go to the Discussions tab in this repository: https://github.com/mdsami/docker-labs/discussions
2. Have a look at the existing discussions in the different sections (General, Idea, Q&A, etc.). Does your question or comment already relate to an open discussion? If so, see if you can find an answer to your question or comment. You can add to an existing discussion by simply commenting there!
3. Is your question or comment (relatively) new? [Open a New discussion](https://docs.github.com/en/discussions/quickstart#welcoming-contributions-to-your-discussions) (right corner of the screen), select under which category your question or comment fits and write it. For searchability purposes, please also include a Label to your discussion. Click "Start discussion" to publish your message.

---

## Using Issues to contribute practical ideas or bug reports
 A relatively easy way to get involved is to open an [Issue](https://github.com/mdsami/docker-labs/issues). You can do this when (among others):
 - You signalled a bug and don't have time or don't know how to fix it yourself (Bug report)
 - You want to provide feedback on a part of the Docker Labs (Leave a review)
 - You have an idea for an extension of the content of the Docker Labs (Suggest changes)
 - You want to suggest edits to the Docker Labs (Suggest changes)

### How to open an issue?
1. Go to the Issues tab in this repository: https://github.com/mdsami/docker-labs/issues
2. On the right part of your screen, click the green button that says "New issue"
3. Choose the issue template that fits your situation best. For example, if you want to suggest edits to part of the Docker Labs, click the "Suggest changes" issue template. If none of the templates fit your situation, choose "Open a blank issue".
4. Fill out the issue template as completely as possible. Provide all necessary details for others to reproduce your results or understand what you are talking about. In case of a bug report, please also let us know what you have already tried and what machine you are using, as this will speed up the debugging process.
5. All done drafting your Issue? On the right of your Issue, please add a **label**, for example: `bug` or `enhancement` so that we know what kind of Issue you wrote (a label is added automatically if you choose an Issue template). If you want, you can also assign a person to review your Issue or link the issue to a Pull Request. However, these are not at all necessary!
6. All done? Click "Submit". 

Congratulations, you have now opened an issue! 🎉

---

## Contributing to Docker Labs content
First of all, how awesome that you want to contribute actual content, thank you!! ✨ The following steps are a guide to help you contribute in a way that will be easy for everyone to review and accept.

The workflow on GitHub is as follows:
1. Copy the repository and all the files in it to your own account (a "fork")
2. Edit the content in your own copy of the repository (edit > "stage" > "commit")
3. Ask the original repository maintainers to merge your edits with the original files (through a "pull request")

### 1. Fork the repository: Copy the repository to your own account
1. To [fork](https://help.github.com/articles/fork-a-repo) the repository, click the `fork` button on the upper right of the repository homepage. This is now your own unique copy of the repository and all the files in it. Changes you make here will not affect anyone else's work, so it is a safe place to try things out!
2. _[Not necessary for beginners]_ If you want to work on your local PC, you can additionally [clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) the repository to your local PC. This simply means that you can edit the files on your PC, without an internet connection.
3. Each time you start working on your copy of the repository, please **first update your copy with the most recent changes**, see [this article](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) for an explanation.

### 2. Edit the content in your own copy (edit, stage, commit)
Here we come to the core of how git and GitHub work. Don't worry, there are multiple ways to edit content, from easy to more advanced.

#### General tips for editing content
- Keep the changes focused. The more content you submit at once, the more work it will be for the person reviewing your work.
- Commit changes each time you made a change. Don't (stage and) commit multiple files at once, unless explicitly necessary.
- Write good, detailed commit messages so that it is clear which changes were made.
- Do not re-write history: don't edit previous commit messages or delete/revert commits, unless explicitly necessary.

#### A. Easiest way: Editing files on GitHub
1. In your fork (the copy of the repository on your own account), [create a new branch](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository#creating-a-branch). A branch is a version of the files _within_ the repository. We want to create a new branch, so that we still always have the clean `main` branch of the repository that has no edits. In the new branch, we can start editing and experimenting. Read more about branches [here](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches). <br> <img src="img/gh-switch-branch.png" width=30%/>
2. When you have switched to your newly created branch, navigate to the file you want to edit. In our repository, all editable Docker Labs chapters can be found in the `chapters` folder of the repository. The files in this folder can be edited.
3. Click the pencil icon ✏️ on the top left of the document and start editing the document.
4. Once finished editing the document, scroll down to the "Commit changes" section and type a commit message. This is simply a line that briefly, but explicitly, describes what changes you made, so that humans reviewing your changes can easily see what you've done.<br> <img src="img/gh-commit.png" width=30%/>
5. Select "Commit directly to the [branch-you-are-working-on]" and click "Commit changes"
6. Go through steps 2-5 for every edit you want to make.

You have now made (a) change(s) in your copy of the repository, congratulations!

#### B. More advanced way: Editing files locally
1. In your fork (the copy of the repository on your own account), [create a new branch](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository#creating-a-branch). A branch is a version of the files _within_ the repository. We want to create a new branch, so that we still always have the clean `main` branch of the repository that has no edits. In the new branch, we can start editing and experimenting. Read more about branches [here](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches). <br> <img src="img/gh-switch-branch.png" width=30%/>
2. Assuming you have cloned your forked repository to your local PC ([commandline](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository), [Rstudio](https://happygitwithr.com/rstudio-git-github.html#clone-the-new-github-repository-to-your-computer-via-rstudio)), you can see the files on your local machine now. Be sure to update your clone with the lastest changes made in the parent repository (commandline: `git pull upstream [branchname]` or `git pull origin [branchname]`, [Rstudio](https://happygitwithr.com/upstream-changes.html)).
3. Switch to the branch you are going to work on (preferably the one matching the chapter you are going to edit): `git checkout [branchname]` (in Rstudio, simply click on the branch name to select which one you want)
4. Make local changes. All editable files can be found in the `chapters` folder. You can open a `.Rmd` file with multiple text editors such as [Visual studio code](https://code.visualstudio.com/), [Atom](https://atom.io/), [Zettlr](https://www.zettlr.com/), [Rstudio](https://www.rstudio.com/), etc.) and, after saving each change, commit it (command-line: `git commit -a -m "commit message"`, [RStudio](https://cfss.uchicago.edu/setup/git-with-rstudio/)). Your changes are now saved locally.
5. Push your commits to the online version of your repository (command-line: `git push origin [branchname]`, [Rstudio](https://happygitwithr.com/rstudio-git-github.html#make-local-changes-save-commit))

### 3. Open a pull request: ask the maintainers to merge your edits
1. In GitHub, navigate to your fork (copy) of the repository
2. Go to the tab "Pull requests" > "New pull request"
3. Make sure the base repository is `mdsami/docker-labs [chapter-branch]` and the head repository is your own repository, e.g., `mdsami/docker-labs[branch-in-which-you-made-changes]`.
4. Describe your edits, e.g., what has been fixed, what has been added, which of the Issues has been addressed, etc. When you're done describing, click "Create pull request"
5. Your pull request will now appear in the [list of pull requests](https://github.com/mdsami/docker-labs/pulls). If you want, you can assign someone to review your pull request. 

Well done, you have opened a PR! One of the owners of the repository will review your commits, may request changes and will finally approve the pull request and merge your changes into the mdsami/docker-labs repository. After merging with the `main` branch, your edits will become visible in the online Docker Labs! Thank you so much for your contribution! 🙏🙏🙏

---

## Recognition for your contribution
We want to recognize each and every kind of contribution that was made to our project. Therefore, we use the [all-contributors specification](https://allcontributors.org/docs/en/emoji-key). After you have made a contribution, one of the maintainers will [add you as a contributor](https://github.com/mdsami/docker-labs/issues/6), so that you will appear as a contributor in the repository [README](https://github.com/mdsami/docker-labs#readme)!
