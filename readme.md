git commands 
loacal working directory (locally we do changes here)
git add takes us to the staging area 

staging area(git commit =m "write any message")
git commit takes our code to local repositary
here we can track the changes by the commit id

local repositarty(here we do git push which takes the file to remort repositary)

remote rpositary(online git hub)
---------------------------------------------------------------------------------------------------------------------------------
git init - initialize your repositary with git and git starts tracking your file
git clone {remort git hub link}
do the changes to the file 
git status {file name}
git add {file name}
git commit -m {any message}
git remote add {remote repositary name } {remote url}
this command connects local repositary to a remote repositary
git push { remote url}
this command push the local repositary to remote
----------------------------------------------------------------------------------------------------------------------------
mkdir-make directory
pwd-present working directry 
cd=change directory
git log (shows all your commits with the commit number)
git branch (shows all your branches in your local repository)
git checkout {commit id}
commit id is the first five characters of the id
git branch {branch name}
create a new branch
git checkout {branch name}
switch to a particular branch
git branch {branch a} {branch b}
to see the difference between the branches
git remote add origin {github link of empty repository}
git push origin master
git pull is used to get the file from remote repository to local repository
--------------------------------------------------------------------------------------------------------------------------------------