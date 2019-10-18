```
git remote -v
git remote add upstream https://github.com/mini-moon/git-notes.git
git checkout -b rebase-from-upstream2
git fetch upstream
git rebase upstream/master
git push --set-upstream origin rebase-from-upstream2
#create pull request rebase-from-upstream2 ---> master 
git checkout master 
git pull origin master
#master is updated.
```

```
git reset --hard origin/master
```
says: throw away all my staged and unstaged changes, forget everything on my current local branch and make it exactly the same as origin/master.

## Notes ##

1. Need *fetch* before *rebase*

2. In Git, "origin" is a shorthand name for the remote repository that a project was originally cloned from.

3. Merge & Rebase https://medium.com/datadriveninvestor/git-rebase-vs-merge-cc5199edd77c
