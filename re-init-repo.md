###1. squash entire repository down to one commit?###
```cd {git-repo}
rm -rf .git #remove the git history
git init #re-init the git repo
git add . 
git commit
git push -u origin master -f #force push to remote 'master' branch
```


