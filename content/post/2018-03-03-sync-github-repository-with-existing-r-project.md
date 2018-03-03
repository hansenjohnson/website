---
title: Sync GitHub repository with existing R project
author: Hansen Johnson
date: '2018-03-03'
slug: sync-github-repository-with-existing-r-project
categories:
  - R
tags: []
header:
  caption: ''
  image: ''
summary: Instructions (mostly for me) to create a GitHub repository for an existing R project, and then use Rstudio to manage version control.
---

Many of the `R` projects I start don't pan out and end up in a scrap directory somewhere, but once in awhile I make enough progress to get worried that I'll lose track of it. That's when I know it's time to get it up on GitHub. This post is mostly just a way for me to remember how to get an existing R project on GitHub. I'm sure there are better ways of doing this in the command line, but I'm still pretty new to Git so I'm sticking with what I know works. Perhaps I'll add a command line version later.

This is loosely based on the combination of [this](https://jennybc.github.io/2014-05-12-ubc/ubc-r/session03_git.html) and [this](http://cfss.uchicago.edu/git05.html) tutorial.

## Step 1: create a GitHub repository

Easy. Go to your github account and click the button to create a new repo. I typically do not initialize with the `.gitignore`, `readme.md`, or `license.md` files, but add them myself manually after the project is up and running.

## Step 2: enable git in Rstudio

1. Open your project in Rstudio and navigate to *Tools* -> *Version Control* -> *Project Setup*

2. Click *SVN/Git* tab and select *git* as the version control system. It will ask you to initialize a new git repo and restart Rstudio

3. After Rstudio reopens, confirm that there is a *Git* tab in the environment pane (which for me, and I think by default, is in the upper right of the IDE)

## Step 3: synchronize with the github repo

Open a terminal and do the following:
```
# move to the project directory
cd Projects/website

# initiate the upstream tracking of the project on the GitHub repo
git remote add origin https://github.com/hansenjohnson/website.git

# pull all files from the GitHub repo (typically just readme, license, gitignore)
git pull origin master

# set up GitHub repo to track changes on local machine
git push -u origin master
```
## Step 4: push files to GitHub

Click the *Git* tab in Rstudio, and then click *Commit*. This will open a window where you can stage files to be tracked (and synced on GitHub). Select all the files you would like to track, write a commit message, then click *push*. This will send all changes to the GitHub repo.

## Step 5: up and running

All you need to do now is remember to commit changes and push them to the GitHub repo. Don't forget!


