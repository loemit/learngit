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
