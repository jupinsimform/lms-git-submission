# Git LMS

## Drop commit
    Remove some commit from feature branch.

## reset
    To remove the last commit from git, you can simply run git reset --hard HEAD^ If you are removing multiple commits from the top, you can run git reset --hard HEAD~2 to remove the last two commits. You can increase the number to remove even more commits.

## revert 
    The git revert command is a forward-moving undo operation that offers a safe method of undoing changes. Instead of deleting or orphaning commits in the commit history, a revert will create a new commit that inverses the changes specified. Git revert is a safer alternative to git reset in regards to losing work.

## Difference bteween reset and revert

| git reset        | git revert          
| ------------- |:-------------:
|git reset does this by moving the current head of the branch back to the specified commit, thereby changing the commit history. | git revert does this by creating a new commit that undoes the changes in the specified commit and so does not change the history.
|![workflow](https://miro.medium.com/max/1400/1*XOx0WZGwLAxVoS-7x_8M3A.png) |![workflow](https://miro.medium.com/max/1400/1*YPzYUfchXmQPtOTYRlyx7w.png)


## Difference between git rest hard,mixed and soft.
![difference](https://www.howtogeek.com/wp-content/uploads/csit/2021/07/f5026f58.png?trim=1,1&bg-color=000&pad=1,1)

## Practical

step 1: create task-5 branch and make some commits on it.
![before](./image/before.png)

step 2: drop commit using git reset command.
![reset](./image/reset1.png)

step 3:for multipal drop use HEAD~n.
![reset-n](./image/reset-n.png)