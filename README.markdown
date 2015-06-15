# Turing School Wiki

## Git & GitHub

### Workflow
*by Andrew Fink*
1. pull from remote master into your local master
2. checkout branch
3. do work, commit.
4. when you're ready to push...don't yet! switch to your local master and pull from master
5. then switch back to your branch and "git merge master", this will merge your updated local master into your branch
6. fix any merge conflicts
7. run your tests, fix any broken tests
8. add, commit
9. now it's ok to push your branch and open a PR "git push origin HEAD" or "git push origin <branch name>"
10. open pull request on GitHub.
11. as soon as a branch is merged to master on GitHub, make your entire team pull from master

### Workflow (Rebase method)
*by Jason Noble*
1. pull from remote master into your local master
2. checkout branch
3. do work, commit.
4. git fetch
5. git rebase origin/master
6. Fix any merge conflicts
7. run your tests, fix any broken tests
8. add, commit
9. now it's ok to push your branch and open a PR "git push origin HEAD" or "git push origin <branch name>"
10. open pull request on GitHub.
11. as soon as a branch is merged to master on GitHub, make your entire team pull from master

