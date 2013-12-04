````
alias: Managing Forks 
weight: 3
layout: docs
clearance: -1
title: CMEP Contribution Documentation
author: Mike Pearson
acknowledgementText: So long and thanks for all the fish.
keywords:
  - github
  - git
  - fork
  - branch
  - pull
  - push
  - status

````

What's all this about forks?
------
One of the main benefits of using `git` is that each contributor works with their own personal copy of the project. You can write to that copy without messing with anybody else's work, but when you want to, you can merge in other people's work or allow them to merge in your work.

GitHub provides a button labelled `Fork` at the top right of any repository home page. Press that button, and a few seconds later you have your own writable copy on GitHub. For example, if Rachel forked CMEPorg/CMEP-sources while logged in as rgt24 on GitHub, it would create rgt24/CMEP-sources there. This becomes her own personal remote. If she uses more than one computer, it's a common store that is always available, and that allows her to keep her machines in sync.

She will clone her remote to create a local copy to work on with:
``` 
git clone https://github.com/rgt24/CMEP-site
```

This document explains how she would connect her local copy to both the CMEPorg repo as well as her personal remote. Locally, the two remotes are represented by local 'tracking' branches. She'll set up branch `site` to track the [main site sources](https://github.com/CMEPorg/CMEP-sources), while her `master` branch tracks [her own copy](https://github.com/rgt24/CMEP-sources).

### References

The [GitHub help docs](https://help.github.com/) go through git and GitHub set up in a sensible and easy to follow fashion.

Start with the BootCamp and read on. It helps you set up git itself, configure your email and userid, and sort out your credentials so that `git push` and `git pull` don't barf.

Also, scroll down to *Managing Remotes* to read how to connect remotes - e.g. to update your sources from CMEPorg/CMEP-sources.
The git docs on this have some helpful diagrams - but do start at the top rather than attempting to pick it up half way through.
That's all in [Remote Branches](http://git-scm.com/book/en/Git-Branching-Remote-Branches) in the Git Book.

There is also some online help. It's written in the Unix man page style, so it's more useful as a reference once you know your way round.

* `man git`
* `man git-xxxx`  where `xxxx` is a `git` command (e.g. `pull`, `push`, `commit`)


### Example 1 - setting up so you can update your fork from CMEPorg.


Let's say your fork is at https://github.com/rgt24/CMEP-sources.git, and you have a local directory
`CMEP-sources` connected to it by `git clone https://github.com/rgt24/CMEP-sources.git`.

The site copy is at `https://github.com/CMEPorg/CMEP-sources.git`. 

#### Add CMEPorg as a remote
First time only

```
$ cd CMEP-sources
$ git remote add CMEPorg https://github.com/CMEPorg/CMEP-sources.git
```
The new remote is visible with `git remote -v`

#### Fetch it from GitHub
First time only

```
$ git fetch CMEPorg

From https://github.com/CMEPorg/CMEP-sources
 * [new branch]      master     -> CMEPorg/master
```

#### Checkout the remote into a tracking branch called 'site'
First time only

```
$ git checkout -b site CMEPorg/master

Branch site set up to track remote branch master from CMEPorg.
Switched to a new branch 'site'
```

This step creates the tracking branch `site` which is visible on `git config -l`. You won't need to create this branch again. 

### Example 2 - pulling subsequent updates from CMEPorg 

On subsequent updates, you simply switch to the site branch and pull the update.

```
$ git checkout site
$ git pull

```

### Example 3 - merging the update with your personal master

#### Pull the site copy

```
$ git checkout site
$ git pull
```

#### Switch back to your own master and merge

```
$ git checkout master
$ git merge site
$ git commit -am'updated from site copy'
```

#### Resolving any merge conflict
This usually works fine, but if there are any files that have been edited in both the site copy and your local master copy there may be some merge conflicts that need to be resolved manually. `Git` will tell you if this is the case. Fortunately there is a good tool to handle this situation.

```
$ git mergetool
```

Use the up-down keys to navigate through the conflicts, selecting the version you want to keep with the left-right keys. When you are finished save and quit. Git will repeat this process until all files with merge conflicts have been resolved. Once done, commit your merged copy.
```
$ git commit -am'updated from site copy'
``` 

### Example 4 - committing edits and pushing back to your fork

```
$ git add .
$ git commit -am'updated from site copy'
$ git push
```

### Example 5 - updating your local copy from your fork

```
$ git pull

```
Again, if someone else has been editing your fork, there may be merge conflicts that you have to manage manually.

### Example 6 - help - I don't know where I am!

Here are a few things that can help you understand

* `git status` -- quick and easy - tells you what state your repository is in and whether anything needs doing to synchronise with remote masters.
* `git log` -- shows you the history of commits to your repo.
* See File history -- Easiest to navigate to the file on GitHub and press the `History` button.
* `git diff <pathname>` -- tells you what has changed in a file as compared to the committed version.
You can also install the `GitGutter` package in `Sublime` to have changes flagged as you edit.
* `git config -l` will show you your configuration, including what remotes and tracking branches you have. Alternatively, look at the file `.git/config`

### List of common git commands

You are unlikely to need any more than these:

```
clone, status, log, add, commit, pull, push, 
remote, checkout, merge, mergetool, diff, config
```


