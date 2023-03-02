# Git_Practical_Exam
## 1. Pull and Merge difference
--> Make example of pull request and two branch merge event.
#### Steps:
    1. Create a feature branch test1, test2 and test3.   
    2. Commit the all feature branch changes and push it in remote repository.   
    3. Create a pull request on github.    
    4. Merge the test1 branch with main branch.
    5. Similarly merge test2 and test3
## 2. Rebase
--> Try to rebase feature branch with master branch 
#### Steps:
    1. In main branch create rebase.html.
    2. Checkout feature branch named "rebase".  
    3. Then commit the rebase branch and push it in remote repository.    
    4. Now to rebase feature branch with master branch using "git rebase main" command.
    5. After rebase is successful in terminal push it to remote repository.
### 3. Change Commit Message 
--> Commit push on commit in feature branch and then change commit message
#### Steps:
   Use git commit -amend -m "modified message" to change your previous commit.

## 4. Cherry Pick
--> Pick some commits from feature branch to master branch
#### Steps:
    1. Created cherry branch and added cherrypick.html file inside it.
    2. Commit all the changes and push that on remote repository.
    3. Copy hash ID of commit that you want to add in main branch.
    4. Checkout in main branch.
    5. performed "git cherry-pick <hash ID>" command.
    6. Push that in remote repository.
## 5. Drop commit
--> Pick some commits from feature branch to master branch
#### Steps:
    1. Created drop branch and added drop.html file inside it.
    2. Made 3 commits
    3. Use Drop commit command on last commit.
        ```
            git reset --hard HEAD^
        ```
    4. Push that in remote repository.



