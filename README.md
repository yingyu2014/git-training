git-training
============

Developer Dana
==========



$ git init myprojectName /*create a directory on your computer
you use git init to make an existing directory of content into a new Git repository. You can do this in any directory at any time, completely locally.

$ cd myprojectName

$ git add .
you run git add on a file when you want to include whatever changes you've made to it in your next commit snapshot. Anything you've changed that is not added will not be included - this means you can craft your snapshots with a bit more precision than most other SCM systems.
For a very interesting example of using this flexibility to stage only parts of modified files at a time, see the '-p' option to git add in the Pro Git book.


$ git status -s
Using the -s option will give you short output. Without that flag, the git status command will give you more context and hints.


$ git commit -m "your message here"

git commit records a snapshot of the staging area

you make changes to your files, then use git add to stage files you want to change, git status and git diff to see what you've changed, and then finally git commit to actually record the snapshot forever.

If you need to collaborate with someone on a project, or if you want to get a copy of a project so you can look at or use the code, you will clone it. You simply run the git clone [url] command with the URL of the project you want to copy.
 you can see the .git subdirectory - that is where all the project data is.

$ git clone URL
$ cd .git



Collaborative Git
==========
Team-centric

$ git pull

$ git merge anyfeature


Customizable Git
==========
Flexible

$ git add -p Myreport.markdown

$ git commit -m ""

$ git log

git@github.com:virtusize/website-jp.git


Git commit
==========
1. Using command line

git status
git add .
git status /*change to stage

2. Using git hub cloud
3. Using loacal git hub software


Git Diff: you run git diff to see details of the git status command - how files have been modified or staged on a line by line basis.
==========

$ git diff
shows diff of what is staged and what is modified but unstaged
So where git status will show you what files have changed and/or been staged since your last commit, git diff will show you what those changes actually are, line by line. It's generally a good follow-up command to git status


$ git diff --cached
If you want to see the staged changes, you can run "git diff --cached" instead.


$ git diff HEAD  
git diff HEAD show diff of all staged or unstaged changes

$ git diff --color-words /*small changes
$ git diff --word-diff  /*lookout small changes to save time
$ git diff --stat  /*show summary of changes instead of a full diff


Git log
==========
$ git log

$ git log --oneline  /*summary: shorten version of logs
$ git log --stat  /*see files changes
$ git log --patch  /*see what contents have been changed
$ git log --patch --online  /*summary plus contents details
$ git log --graph --all --decorate --oneline  /*summary plus contents details


Remove
==========
$ git rm fileName/*Suitable for removing single file
$ git status /*to stage the file
$ git commit -m ""


$ git add -u .  /*For Serious delete ; .means current working directory

$ git rm --cached fileName   /*untrack the file, leave this file there instead of deleted, 
$ git status




Move file
===========
$ git mv oldPass newPass





























