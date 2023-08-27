# GitHubInfo
This is My First GitHub Repository, From this Repository, I am going to Start My Journey as a Open Source Developer, and Contribute to Many Many Projects. 
1. Configuring Git
   git config --global user.name "My Name"
   git config --global user.email"someone@email.com"
   git config --list

2. Clone & Status
   Clone - Cloning a repository on our local machine
   git clone <- some link ->

   status - displays the state of the code
   git status

Note : cd -> change directory
Note : clear -> Command to clear the terminal.
Note : ls -> Command to show files in Repository.
Note : ls -a -> Command to show hidden files in Repository.

After writing git status we will get Info like this.
   1. untracked
   new files that git doesn't yet track.

   2. modified 
   changed

   3. staged 
   file is ready to be commited

   4. unmodified
   unchanged

3. Add & Commit
  
   add - adds new or changed files in your working directory to the Git staging area.
   git add <-file name->

   commit - it is the record of change
   git commit -m"some message"

   Note : git add . -> will change all files.

4. Push Command
   push - upload local repo content to remote repo 
   git push origin main/branch name

5. Init Command 
   init - used to create a new git repo

   git init

   git remote add origin <-link->

   git remote -v (to verify remote)

   git checkout -b branchname (to originate and add new branch)

   git add . - Add the changes.

   git commit -m "commit message"

   git push origin main/branch name.

Note :
   git branch (to check branch)
   git branch -M main (to rename branch)

Summarized Work Flow:
   Create GitHub Repo -> Clone -> Do fix Change/Code -> Add -> Commit -> push  

6. Branch Commands 
    
    git branch (to check branch)

    git branch -M main (to rename branch)

    git checkout <- branch name -> (to navigate)

    git checkout <-new branch name-> (to create new branch)

    git branch -d <- branch name -> (to delete branch)