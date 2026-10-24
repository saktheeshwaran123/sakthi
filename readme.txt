Git Comments:

 - git config --global user.name "__" -> use your user name
 - git config --global user.email "__" -> use your user email
 - git config --global --list -> used to view your name and email
 - git config user.name -> view user name
 - git config user.email -> view user email
 - git config init.defaultBranch main
 - git init -> initialize your git id
 - git status -> used to view your git on which state

 // add
 - git add "file_name" -> used to add your file -> 1 file add
 - git add "file_name" "file_name" -> used to add your two or many file -> 2 or more file add
 - git add . -> used to add all file

 // commit
 - git commit -m "__comment__" -> used to commit your files -> ex: version 1, version 2.3 etc,..
 - git log -> used to view your all commit history -> each commit have a unique_code
 - git checkout unique_code -> view that commit 
 - git checkout main -> while you view commit if you change anything in file after using this code to checkout , the file is modify
 - git checkout -f main -> this force to main used to dismiss all change , the file look like before commit you viewing the file
 - q - used to exit

 // branch 
 - git branch "branch_name" -> used to create a branch 
 - git checkout "branch_name" -> used to switch a branch  
 - git checkout -b "branch_name" -> used to create new and switch a branch at the same time 
 - git branch "new_branch_name" "source_branch"
 
 //push
 - git push --set--upstream origin "branch_name" -> upload a file and update file on branch
 - git push -u "branch_name" -> same us before ^^^
 - git push -> once you do before one of the method after any push use this in same branch
 
 //pull
 - git pull 

 //merge
 - git merge "branch_name"

 //reset
 - git reset "unique_code"
 - git reset --soft "unique_code"
 - git reset --hard "unique_code"

 //revert
 - git revert "unique_code"

 //stash
 - git stash
 - git stash list 
 - git stash apply 'stash@{id}'

 
