# Welcome to the NYCIST Github!

This repo will serve as a helpful starting place for those who want to contribute to the NYCIST Github, or simply want to host their code in a private repo.

If you haven't used Github before or are unfamiliar with `git` that's OK!  This will hopefully help you get started on how to use these tools and contribute to this organization.

## About Github

Github is one of several different code hosting services ([Gitlab](https://gitlab.com/), [Bitbucket](https://bitbucket.org/), among others) that have built a platform around `git` and providing coders a robust toolset to create, contribute, collaborate, and share code.

Know that just like how learning to use a traditional word processor carries over when using Google Docs, for example, learning to use Github will also allow you to more easily use these other services.

## Helpful Resources

### Learning Git & Github

If you're not familiar with `git`, take a look at this [getting started doc.](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

Github also has a really nice [learning resources page](https://help.github.com/articles/git-and-github-learning-resources/) as well as a [document series](https://guides.github.com/) to help you understand and get started with `git` & Github.

Additionally, Github offers a [Learning Lab](https://lab.github.com) which allows you to learn Github through a number of practical projects through [different courses](https://lab.github.com/courses) from within Github.  So, you can start learning Github by actively using it.

Here are also a series of helpful videos if you'd prefer to watch, rather than read:
- [Github Guides YouTube Channel](https://www.youtube.com/githubguides)
- [Github Foundations YouTube Playlist](https://www.youtube.com/playlist?list=PL0lo9MOBetEHhfG9vJzVCTiDYcbhAiEqL)

### Github Desktop

Especially when starting out, it can be difficult for those not as comfortable on the command line to get the workflow of using `git`.

To help ease this transition, Github makes a great tool called [Github Desktop](https://desktop.github.com/), which removes a lot of the initial learning curve when making commits.  If you need a reason why you'd use the tool, take a look at their ["Who is it for?"](https://github.com/desktop/desktop/blob/master/docs/process/what-is-desktop.md) document.  Definitely worth a download.

### Text Editors

There are many different freely-available text editors. Some are more advanced than others, but the best way to find one that works best for you is to try one. Several recommendations are below:

- [BBEdit](https://www.barebones.com/products/bbedit/index.html)
	- You can request a free educational license from the company so you can use the software without being periodically nagged to pay for the full version.
- [Sublime Text](https://www.sublimetext.com/)
	- Will periodically suggest to pay for the software after so many saves, but otherwise can use completely free.
- [Atom](https://atom.io/)
	- A more advanced editor in that you can install additional 'packages' to extend its features and functionality.  As one example, you can use the [Teletype](https://atom.io/#teletype) package to create a shared workspace using the editor itself, allowing real-time code collaboration

## About Git 

### Git in a Nutshell

`Git` is system of version control that focuses on the differences (deltas) between the state of files at different points in time.

Imagine you are writing a long essay over a series of weeks.  Using a traditional text editor (like Word), as you add, change, and remove text in the file, every time you save the essay it overwrites the original file.  As a result, if you ever wanted to look back at a prior version of your essay, or to rollback a specific undesirable change, unless you had a backup of this file somewhere this would not be possible.

Now imagine you're working on that same essay in a group.  As time goes on and changes are made, how do you determine who in the group contributed what in the essay?  Additionally, if you or anyone made a change (or series of changes) and you wanted to determine when and why the change was made, how would you do this?

`Git` then is the answer to these version control & collaboration challenges, but specifically designed for coders.

### Git Workflow

You can find a nice `git` flow here: [https://guides.github.com/introduction/flow/](https://guides.github.com/introduction/flow/)

The basic workflow of a computer with `git` installed is as follows:

1. A local repository (repo) is made. This is just a folder, but is crucially configured for `git` (via [init](https://git-scm.com/docs/git-init)).

2. One or more files or folders are created within the repo. `Git` assesses the differences between the previous save ([commit](https://git-scm.com/docs/git-commit)) of the repo and current state of all the files and folders within to determine what's changed.

3. When all desired changes are made, these files and folders need to be put in a "staging" area ([add](https://git-scm.com/docs/git-add)) before they can be committed.  This step in the process makes more sense as you use `git` more.

4. Once all desired files and folders are "staged", commit (write) these changes.  A new snapshot is taken and a comment is written to indicate why the change(s) was made for documentation purposes.

## Github for Education

One of the benefits of using Github is that they offer [Github for Education](https://education.github.com/). One of the many benefits of this program is that approved organizations can create an unlimited number of private code repositories.  Normally, Github and others charge to host private repos, as it's encouraged to create public repos for freely sharing code and projects with the larger community.

However, especially when you're dealing with student work or things you want to share with a select group of people, private repos are ideal.

Any education institution can request to [join Github Education](https://education.github.com/discount_requests/new), but you can request these can be hosted within the NYCIST Github.

## Contributing to NYCIST

We hope that regardless of your comfort level with `git` and coding largely, that you will share your code, projects, and generally contribute & help others within the community!

### How to Request Repos in NYCIST

If you wish to have a repository created or hosted in NYCIST, you have a few options:

1. Submit an issue in this NYCIST repository requesting a repo.
	- Be sure to provide **all** requested information in the issue template, as this will allow us to create your repo more quickly.

2. If you have an existing public repository that you would like to move to NYCIST, submit an issue and link to your repo.  We'll fork your repo, keep it public or make it private, and give you full access to it in NYCIST.
	- If you are keeping the new NYCIST repo public, please be sure to keep your original repo but update your README to indicate the new location in NYCIST.

3. Send a message in the #github-projects channel in the NYCIST Slack requesting a repo for your Github account.  We'll create it and give you access to the repo.

### Documentation in NYCIST Github

[Writing & formatting on Github](https://help.github.com/categories/writing-on-github)

## TO-DO

- [x] Write README
- [ ] Create issue template for repo requests