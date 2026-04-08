# MY FIRST REPO

## Termanial steps for creating a Repository
-  (Must DO for every project you wish to push to Github.)
1. Open terminal and make sure it is in the correct file.
2. Initialize repo tell github to track. Create repo only on local. 
-    Terminal command  `git init`
-  `pwd` tells you what directory/file you are in.
3. Create the online repo to connect with. Go to Github.com 
4. Give it a name and hit `Create Repository` 
  -  this command links your local repo to remote destination 
    - check by running command `git remote -v` shows a remote destination if you have one.

  ## Steps to make and commit a new version of your project.
 1. `git add .` - add all files in this directory to a new project version.  **  This DOES NOT commit ,just stages them. This changes can still be overwritten.

2. `git commit -m commit message` - this command makes a commit and gives it a message.

 ## Steps to PUSH commits to github.com
 1. `git push origin -u main` - pushes all commits to github.com
 2. All subsequence pushes `git push`
  
  ## Vocab:
  -  `commit` - to save a version, you can commit locally, oush commit to git hub
  - `push` - to push commits to online repository.