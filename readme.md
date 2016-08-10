Git is a distributed version control system.
Git is free software.
Git tracks changes of files.


![git flow chart](http://i.imgur.com/7ZtM0rQ.jpg)
![repository](http://i.imgur.com/TEJbYMR.jpg)

git log --pretty=oneline
git reset --hard HEAD^
git reflog

want to discard last record?
	git checkout -- readme.txt  //clear working space,replaced by repo  
	git reset HEAD file	    //unstage,then you can use checkout

git remote add origin git@github.com:pia/learngit.git
git remote set-url origin git@github.com:pia/learngit.git

sudo git config --global core.autocrlf false

![branch]([Imgur](http://i.imgur.com/Bw4bwUV.png)
Creating a new branch is quick.
	git branch dev=git branch dev;git checkout dev
	git branch master
	git merge dev
	git branch -d dev
