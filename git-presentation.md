# [fit] How to use ~~GitHub~~ git

### Let's look into it at KIT

----

# What do I use git for?

## To track changes on:

- a source code
- a LaTeX manuscript
- a PDF presentation

----

# What do I use git for?

## To collaborate with others

- work on a presentation with collaborators
- work on a source code with your coworkers
- ask for a review of your article to your co-authors

----

# What do I use git for?

## To share my work

- public sharing on a public GitHub repository (with a license! Mandatory in Germany)
- private sharing to some collaborators

----

# Vocabulary[^1]

[^1]: All of it here: <https://git-scm.com/docs/gitglossary>

----

## git

> An open source, distributed version-control system.

## GitHub

> A platform for hosting and collaborating on Git repositories.

Alternatives: GitLab, Bitbucket, SourceForge, Google Cloud Source Repositories…

----

## (git) repository

> Where all your changes are stored.

----

## commit

> A state of changes. Every commit is identified by a reference (the `sha1`).

A commit contains a lot of information such as: author, commiter, message, description, dates…

----

## tree

> The stored representation of your git repository.

![inline](./image-20200621213901273.png)

----

## branch

> An active line of development. The most recent commit on a branch is referred to as the tip of that branch.

![original inline 100%](./public-small-1.png)

----

## "master" branch

> Common used name for the default branch.

You could use `main` as well if you don't want to use `master`, or any name you want [^2].

[^2]: We'll use `master` here as it's easier because I use `master` for ~12 years now.

----

## local repository

> The repository on your machine.

----

## remote repository

> Identifies your repository on a remote server (like GitHub).

There is _almost always_ a local and a remote repositories. It's rare (and dangerous) to only have a local repository. You use the remote as a backup server! What a nice feature! 💪

----

## "origin"

> The most common used default remote name. 99% of the time the default remote will be named `origin`.

----

## master or origin/master?

> `master` alone is your local branch named `master`.

> `origin/master` is the `master` branch on the `origin` remote.

----

## HEAD or head?

> `HEAD` 

----

commit

----

clone

----

# Visualization

----

Example repository

----

tig

module load git/2.27.0-gcc-9.1.0

Mistral DKRZ: /sw/rhel6-x64/vcs/tig-2.2.1

https://github.com/jonas/tig/releases

----

# Initializiation

----

git config 

ssh key generation

----

git init

----

git clone 

----

git status

----

git log

----

# Protocol

----

git add

----

git commit

----

git push

----

git fetch

----

git full

----

.gitignore

----

git reset

----

git checkout

----

git branch

----

Safety rules

Do not delete your .git directory!

----

# Simple example

----

Step 1. Log in to github and create your own private repository.

----

Step 2. Clone the repository locally and create a .txt (or .py or .f90) file to add.

----

Step 3. Adjust the file and make a second commit.

----

Step 4. Make some changes on github and pull these to your local machines.
