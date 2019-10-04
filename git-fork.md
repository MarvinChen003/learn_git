```
git remote -v
git remote add upstream https://github.com/mini-moon/git-notes.git
git checkout -b rebase-from-upstream
git fetch upstream
git rebase upstream/master
git push --set-upstream origin rebase-from-upstream
#create pull request rebase-from-upstream ---> master 
git checkout master 
git pull origin master
#master is updated.
```