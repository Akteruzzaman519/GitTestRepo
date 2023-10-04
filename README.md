This is my local repository 

git normar flow 

    loacal repo
    git clone
    git add 
    git commit -m "commit message"
    git remote add origin  "url here" // origin name can be anythings
    git remote  // check to origin check
    git remote -v  // which url connect to the URL
    git branch  // check all branch for current
    git branch -M main  // current branch name rename 
    git push -u origin main // push current repo to remote repo sent code 
    

    Branch command

    git branch  (to check branch)

    git branch -M main  (to rename branch)

    git checkout branchName  (navigate to branchName)

    git checkout -b newBranchName   (to create a new branch)
    git branch -d branchName  (to delete branchName)

    Merging Code

    way one 
    git diff branchName (to compare commit branch, file more)

    git merge barnchName  to merge to branch

    way two 
    Create PR


    Pull Request 
    it lets you tell other about changes you have pushed to a branch in a repo on

    pull command 
    git pull origin BranchName

    used to fetch and download content from remote repo and immediately update the loacal repo to match that content


    Resolving Merge Conflicts
    An event that takes place when Git is unable to automatically resolve difference in code between two commits


    manually reoved for  Accept current changes  Accept incomming changes  Accept both changes compare changes 


    Undoing Changes

    case  1 : Stage changes 
    git reset fileName
    git reset    // current add all file or changing file previous state

    case 2 : commit change (for one commit )
    git reset HEAD~1  remove one commit to to previous commit stage 

    Case 3 : commit changes for many commit 

    git reset commitHash
    git reset --hard commithash
    
