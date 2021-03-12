# ﻿Week 1|Batch 5 |NIT Bhopal| Sharad Rai (haeckerzz)

## Git commands

### i) Setup a Local Repository:


    - cd /path/to/folder
    - git init
    - git add .
    - git status
    - echo "My first assignment" >> README.md
    - git add.
    - git commit -m "First time import to github from local through main branch"

### ii) Setup a remote Repository:


	- git branch -M main
	- git remote add origin https://github.com/Haeckerzz/ps_pjp_2021_a1.git
	- git push -u origin main



### iii) Create local Branch (feature_branch, qa_branch, dev_branch, delivery_branch):


	- git branch feature_branch
	- git branch qa_branch
	- git branch dev_branch
	- git branch delivery_branch



### iv) create remote branches:


	- git push origin –all



### v) Add files, Make changes to existing files , Add folders, Remove folders, remove files :


	- echo "Adding new file">>file1.txt
	- echo "Adding another file ">>file2.txt
	- git add .
	- git commit -m "adding files for operation like add, delete"
	- git push -u origin main
	- git rm -f file2.txt
	- mkdir Folder_new1
	- git add .
	- git commit -m "we have created folder and removed file2.txt"
	- git push -u origin main
	- cd Folder_new1
	- echo "inside new_folder_1">>file_1_v1.txt
	- git add .
	- git commit -m "new folder with new file "
	- git push -u origin main



### vi) Check-in, Stage, Commit, Push files into feature\_branch:


	- git checkout feature_branch
	- echo "code in feature branch">>feature.txt
	- git add .
	- git commit -m "feature file is committed "
	- git push origin feature_branch



### vii) Promote code from feature branch to dev branch pull via pull requests:


	- git checkout dev_branch
	- git pull origin feature_branch
	- git add .
	- do changes in feature.txt using sublime
	- git commit -m "checkedfeature file by dev"
	- git push origin dev_branch



### viii) Check-out the latest code from remote branch to local branch:


	- git pull origin feature_branch


### ix) Explore the difference between Checkout vs Pull”:


	- Checkout:	 git checkout branch_name
			It help us to update the code the through specified branch and we can easily see the history and manage the changes else it gives merge conflict.
      
      
	- Pull:		git pull branch_name

			It downloads the repo to local pc and brings changes from the remote repository.

### x) Get two people to make Change to the same file, check in & handle merge conflicts:


	- Since both the feature_branch and dev_branch tried to changed the code inside feature.txt then but then we finally resolved the merge conflicts

### xi) Ensure the code is in Sync with the latest changes across all branches:


	- Code was then pulled across all branches using git pull branch_name



## Basic usage using the GUI Client (GitHub Client):


	- In this I have used the GUI of GitHub do all the changes which are done earlier using cmd



## On the ground day to day scenarios


	- Reset/ revert:  $ git revert HEAD

	- Stash:  $ git stash

	- Rebasing: $ git rebase branch_name

	- Git log, status & reflog: $ git reflog


