# Turing School Wiki
*Purpose: To capture some of the useful links and references that would otherwise be lost in the Slack ether.*

## Your Questions About Turing Answered Here
See [Turing School FAQs](faqs.md)
(Mostly for new students)

## Module-Specific
See [Facts by Module](facts-by-module.md)

## Non-Module Specific

### Languages and Frameworks
See [Language Resources](language-resources.md)

### Git & GitHub
#### Workflow
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

### Lightening Talks

There are 3 purposes for public speech: to inform, to persuade, and to entertain. Here's a resource for your invormative, 5-minute lightening talk: http://www.usd389.net/vimages/shared/vnews/stories/4d221c541bf5e/InformativeSpeech.pdf

#### Workflow (Rebase method)
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

#### Workflow (using Waffle.io)
*by Jason Wright & Adam Caron*

1. add issue in Waffle.io
2. create feature branch
3. do some code
4. push branch
5. submit pull request, with description that "closes 'issue#'" (ie. "closes #1")
6. other person reviews pull request
7. (if merged) git checkout master
8. git pull origin master
9. merge master into branch

#### Workflow (ThoughtBot)
[Git Protocol Guide](https://github.com/thoughtbot/guides/blob/master/protocol/git/README.md)

#### Git In Depth Basics for non-programmy People
*by Dave Maurer*
[Public Gist](https://gist.github.com/davemaurer/cd97d99309aa6744b344)
