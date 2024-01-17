# Git_Branching
learning Git Branching
## Git branching
1.Enables multiple people to work on the same project.

## Git commands

1. create a branch
       `git branch "branchname"`
   
2. Switching between branches
    
       `git switch "branchname"`
    
3. Directly switching to a new branch
   
	`git checkout -b "branchname"`
   	

4. Merging: (completing a feature/fix errors or bugs)
   
       `git merge sourcebranch`
    

5. Resolve conflicts
    
       `git mergetool`
     
6. Deleting a branch
  
    `git checkout -d "branchname"`
  

7. list all branches

 `git branch`
 
 8. A list of extra commands
 `git branch -v`
 
 `git status`

 -list merged commits
 `git branch --merged`

 -list unmerged commits
 `git branch --no-merged`

 #### Bonus command
 ```code
    <hl> git log </hl> 
 ```