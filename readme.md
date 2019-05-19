https://www.youtube.com/watch?v=SWYqp7iY_Tc


## GIT ignore:

.gitignore is a file that enlists the files and directories, that will not be managed by GIT
so even if you make a change, do git add and then do git status, those files that you had mentioned will not be in the staging area to be commited

## GIT Branch:

If you create a new branch
and then
Add files in it and add and commit it
and them
switch back to the old branch
you will freaking see the files disapperang even in your file explorer gui

so actually the files change! the directory changes in the GUI as well


VERY INTERESTING IDEA

## GIT MERGE

then later on you could always got to the master and do 
git merge mw167d
what it will do is get everything from mw167d! and then there wont be any difference!

SMOOTh - Youtube video is Git & github crash course for beginners by Traversy Media


## FOR GITHUB
Create a repository, with the name
git remote add origin https://github.com/maisamwasti/git_test.git
git push

#### To another repository
git clone https://github.com/maisamwasti/Rainbow-Poem.git 
vi Poem-India
git add Poem-India
git commit -m "Changed Poem-India"
git push -u origin master

#### create another branch there
git branch cats
git checkout cats
vi cats.txt
git commit -m "adding new branch called cats and adding cats.txt there"
git push -u origin cats
