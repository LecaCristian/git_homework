# What is GIT
Git is a distributed version control system that is commonly used for tracking changes in source code during software development.


# Understanding the GIT 
Think of Git as a time machine for your work. It saves snapshots of your project's progress, so you can go back to any point in time.
This is super helpful if something goes wrong—you can always go back to the last working version.

# Commands in GIT
* `GIT CLONE <REMOTE REPO LINK>` - CLONE THE REPOSITORY FROM THE REMOTE
* `GIT STATUS` - SHOW STATUS OF CURRENT HEAD
* `GIT CONFIG --GLOBAL USER.NAME/USER.EMAIL`
* `GIT ADD` -ADD ALL UNTRACKED CHANGES TO COMMIT
* `GIT ADD.` - ADD ALL UNTRACKED CHANGES TO COMMIT
* `GIT RM --CACHED <FILE_NAME` - REMOVE FILE
* `GIT STASH, GIT STASH POP/APPLY` - SAVE OR EXTRACT FROM CACHE
* `GIT COMMIT -M "<COMMIT_MESSAGE>"` - COMMIT THE CHANGES
* `GIT LOG --ONELINE` - DISPLAY ALL COMMITS FOR THE BRANCH THAT YOU'RE ON
* `GIT COMMIT --AMEND` - CHANGE YOUR LATEST LOG MESSAGE OR TO MAKE MODIFICATIONS TO THE MOST RECENT COMMIT.
* `GIT BRANCH` - SHOW THE LIST OF BRANCHES
* `GIT BRANCH "<BRANCH_NAME>"` - MOVE TO BRANCH
* `GIT BRANCH -D "<BRANCH_NAME>"` - DELETE THE BRANCH
* `GIT CHECKOUT "BRANCH_NAME"` - MOVE TO BRANCH
* `GIT CHECKOUT -B "NEW BRANCH_NAME"` - CREATE NEW BRANCH AND MOVE TO IT
* `GIT MERGE` - MERGE CHANGES
* `GIT PUSH` - PUSH CHANGES TO REMOTE
* `GIT PUSH -FORCE` - PUSH FORCED THE CHANGES TO REMOTE REPOSITORY
* `GIT PULL` - PULL CHANGES LOCALLY FOR A SPECIFIED BRANCH FROM THE REPOSITORY
* `GIT REBASE` - USE GIT REBASE TO COMBINE COMMITS AND MODIFY HISTORY OF A BRANCH.
* `GIT FETCH` - FETCH ALL THE BRANCHES FROM THE REMOTE REPOSITORY
* `GIT SQUASH` - COMBINE MORE COMMITS INTO ONE
* `GIT RESET [--SOFT | --HARD] <COMMIT> [<FILENAME>]` - RESETTING REPO WITHOUT CREATING NEW COMMIT
* `GIT REVERT "<COMMIT_NAME>"` - RESETTING REPO WITH NEW COMMIT

* Rule one
 **DO NOT FORCE PUSH IN MASTER** 
* Rule two
* **Always commit your relevant changes**

# Last Commit
* Challanges : I think it was interactive and quite easy to understand. There were no issues
* New things that i have just learned : **git squash** was something new that i undestand with this training
* Feedback : Keep going!