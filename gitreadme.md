<!-- clone project from github push code  -->

git clone https://github.com/Rock257/Analog-Clock.github.io.git

<!-- cd -->
cd  -change directory

<!-- clear terminal  -->

clear 

<!-- file - 1 hidden  2 normal --> 

ls -a 

<!-- check status - display the status of code --> 
git status


<!-- to add we have to commit the file to  -->

<!-- add -->

git add file name 

git add .(to add all  file together)

<!-- commit  : it is the record of change   -->

git commit -m "some message"

<!-- push  - upload local repo to remote -->

git push main origin




<!-- push code from the file or folder  -->

1. git init

<!-- check status -->

2.git status

<!-- add files -->
<!-- this add allfiles together -->
3   git add .


<!-- commit change and check status -->
4. git commit -m 'all  new files added'


<!-- create new repo on github where we want to push the code -->


<!-- add rmoter orign  -->
5 . 

git remote add origin <- link ->

<!-- 6. to verify the origin  -->

git remote -v

<!-- 7  to check branch -->

git branch

<!-- 8. to rename branch -->

git branch -M main

<!-- 9 push  -->

git push origin main

git push -u origin main






<!-- 
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Rock257/tesrt.git
git push -u origin main 
-->