git-training
============

Developer Dana
==========

$ git init myprojectName /*create a directory on your computer

$ cd myprojectName

$ git add .

$ git commit -m "your message here"


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

Git Diff
==========
Tell you what is you have been done

$ git diff /*files are different to your stage

$ git diff --staged /*to figure what files are different between your stage area and your last commit

$ git diff HEAD /* tell you all the changes you made since your last commit

$ git diff --color-words /*small changes
$ git diff --word-diff  /*lookout small changes to save time
$ git diff --stat  /*only tells you what files changed


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





























