# GIT Basics
Git Commands
Basics
git add is a command used to add a file that is in the working directory to the staging area.
git commit is a command used to add all files that are staged to the local repository.
git push is a command used to add all committed files in the local repository to the remote repository. So in the remote repository, all files and changes will be visible to anyone with access to the remote repository.
git fetch is a command used to get files from the remote repository to the local repository but not into the working directory.
git merge is a command used to get the files from the local repository into the working directory.
git pull is command used to get files from the remote repository directly into the working directory. It is equivalent to a git fetch and a git merge .

GIT
Open CMD /Git Bash
-	git config --global user.name "priyarajput123"
-	git config --global user.email  priya9156rajput@gmail.com
-	git init                    --to create new repository
-	cd..                               move back
-	pwd full path of the folder
-	git add.               -> add everything which is present on tht folder
-	git add C:\Users\p.pushparaj.rajput\Downloads\test12.txt             -test12.txt file add full path
-	git commit -m "First Commit with test12.txt"
-	git log                             commit message with Head master / Autor name /Date & time
-	git remote add origin https://github.com/priyarajput123/Gitbasics.git
-	git branch -M main
-	git push -u origin main
-	$ git remote set-url origin https://github.com/priyarajput123/demo123.git
-	

mkdir folder_name
cd folder_name
git add .
git commit -m "test"
# set remote url via UI
git push

https://dillinger.io/                - online editor

# Changes r made in file
git add .
git status
$ git commit -m "file updated"
$ git pull origin main                 -> To full files from repos
git fetch                                 ->To check how many branches r present 
git branch -a                            ->to check hidden files
git checkout -b feature1           ->to create new branch //Switched to new branch feature1
git branch branchname

git fetch -p                                   ->which branch is deleted
$ git push origin HEAD                     ->to push code in feature file
$ git push origin HEAD:main                    ->to push code main Branch
$ git checkout main                           -> to jump back to main branch 
git  merge feature 4          -> to merge 
git push –set-upstream origin main                         -to puhs changes from main to feature branch
git stash                                                        tempory chages will move here
git stash  list
git diff file name                              ->>to show file changes

resolve conflict
git merge tim branch

Setting ->Developer Setting->Personal access tokens ->Generate new token ->Fill details->Generate
https://www.youtube.com/watch?v=tk4s7o-ZGhk
https://www.youtube.com/watch?v=uFaYgSVzy3w


