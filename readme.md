This is git project for completion of Git assignment-2 for this course.This project has two feature branch with main branch. "feature-1" and "feature-2". We aregoing to merge these two feature branches then delete them from both repository.
Commands
$ git init
$ git remote 
$ git remote add origin git@github.com:al0314/rebase-practice.git
$ touch readme.md 
$ vim readme.md
$ git add .
$ git commit -m "Update readme.md file with project decription"
$ git status
$ git log
$ git co -b feature-1
$ touch feature-1.txt
$ git add .
$ git commit -m "Add text file for feature-1"

$ git co -b feature-2
$ touch feature-2.txt
$ git add .
$ git commit -m "Add text file for feature-2"
$ git status
$ git co master

$ git fetch origin master
$ git rebase origin/master
$ git push origin feature-1

$ git fetch origin master
$ git rebase origin/master
$ git push origin feature-2

$ git branch -d feature-2
$ git co master

$ git branch -d feature-1

$ git pull origin master

$ vim readme.md
$ git add .
$ git commit -m "Update readme.md file with all commands"
$ git push origin master
