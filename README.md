# Training for ijuzhong

git version 2.19.0

`git clone git@github.com:JIN0759/demo.git`

[2.1 Git Basics - Getting a Git Repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository){:target="_blank"}

# Attention:
If you want to push to github.com, use:

`$ git push origin master:master `

Or: 
comment this line on ~/.gitconfig 

    #push = refs/heads/master:refs/for/master

# Research
[Understanding the GitHub flow](https://guides.github.com/introduction/flow/){:target="_blank"}

[Issues with git-flow](http://scottchacon.com/2011/08/31/github-flow.html){:target="_blank"}

[Migrating SVN2Git Utility](https://services.github.com/on-demand/downloads/subversion-migration/){:target="_blank"}

# How
[How to write README file on github.com? ](https://help.github.com/articles/basic-writing-and-formatting-syntax/){:target="_blank"}

# branch dev
```shell
git co -b dev origin/dev 
vim README.md 
git ci -am 'modify readme from dev'
git push origin dev
```

# Syntax highlighting
```php
echo "test pull request.";
```

