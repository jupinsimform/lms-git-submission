# Git LMS

## Pull and Merge difference
    Make example of pull request and two branch merge event.

## Difference Between a Pull Request vs. Merge Request
    A Git pull request is essentially the same as a Git merge request. Both requests achieve the same result: merging a developer’s branch with the project’s master or main branch. Their difference lies in which site they are used; GitHub uses the Git pull request, and GitLab uses the Git merge request.


![pull](https://static.javatpoint.com/tutorial/git/images/git-pull2.png)

| Command        | Description          
| ------------- |:-------------:
|git pull  | Fetch + merge
|git merge bugfix | Merges the bugfix branch into the current branch
|git merge --no-ff bugfix | Creates a merge commit even if FF is possible
|git merge --squash bugfix | Performs a squash merge
|git merge --abort  | Aborts the merge
|git branch --merged | Shows the merged branches
|git branch --no-merged | Shows the unmerged branches


step 1:create a feature branch
![feature](./image/feature.png)

step 2:comapre and pull request in feature branch
![image1](./image/1.png)

step 3:create pull request
![image2](./image/2.png)

step 4:merge pull request
![image3](./image/3.png)
![image4](./image/4.png)

step 5:after mergeing with master commit
![show commmit](./image/commit.png)