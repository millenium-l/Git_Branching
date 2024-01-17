# Git_Branching
learning Git Branching
## Git branching
1.Enables multiple people to work on the same project.

## Git commands

1. create a branch
   ```bash
       git branch "branchname" 
   ```
2. Switching between branches
    ```bash
       git switch "branchname"
    ```
3. Directly switching to a new branch
   ```bash
	git checkout -b "branchname"
   ```	

4. Merging: (completing a feature/fix errors or bugs)
   ```bash
       git merge sourcebranch
   ``` 

5. Resolve conflicts
    ```bash
       git mergetool
    ``` 
6. Deleting a branch
  ```bash
    git checkout -d "branchname"
  ```

7. list all branches

 'git branch'
 'git branch -v'
 
 'git status'

 -list merged commits
 'git branch --merged'
 -list unmerged commits
 'git branch --no-merged' 