https://www.youtube.com/watch?v=SWYqp7iY_Tc


## GIT ignore:

.gitignore is a file that enlists the files and directories, that will not be managed by GIT__
so even if you make a change, do git add and then do git status, those files that you had mentioned will not be in the staging area to be commited__

## GIT Branch:

If you create a new branch__
and then__
Add files in it and add and commit it__
and them__
switch back to the old branch__
you will freaking see the files disapperang even in your file explorer gui__
__
so actually the files change! the directory changes in the GUI as well__

__
VERY INTERESTING IDEA__

## GIT MERGE

then later on you could always got to the master and do__ 
git merge mw167d__
what it will do is get everything from mw167d! and then there wont be any difference__
__

SMOOTh - Youtube video is Git & github crash course for beginners by Traversy Media
__

## FOR GITHUB
Create a repository, with the name
git remote add origin https://github.com/maisamwasti/git_test.git__
git push -u origin master__


#### To another repository
git clone https://github.com/maisamwasti/Rainbow-Poem.git__ 
vi Poem-India__
git add Poem-India__
git commit -m "Changed Poem-India"__
git push -u origin master__

#### create another branch there
git branch cats__
git checkout cats__
vi cats.txt__
git commit -m "adding new branch called cats and adding cats.txt there"__
git push -u origin cats__
