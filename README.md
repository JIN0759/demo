# Training for ijuzhong

git version 2.19.0

`git clone git@github.com:JIN0759/demo.git`

[2.1 Git Basics - Getting a Git Repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

# Attention:
If you want to push to github.com, use:

`$ git push origin master:master `

Or: 
comment this line on ~/.gitconfig 

    #push = refs/heads/master:refs/for/master

# Research
[Understanding the GitHub flow](https://guides.github.com/introduction/flow/)

[Issues with git-flow](http://scottchacon.com/2011/08/31/github-flow.html) 

[Migrating SVN2Git Utility](https://services.github.com/on-demand/downloads/subversion-migration/) 

# How
[How to write README file on github.com? ](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

# branch dev
```
git co -b dev origin/dev 
vim README.md 
git ci -am 'modify readme from dev'
git push origin dev
```
