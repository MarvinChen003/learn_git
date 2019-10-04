####ways of git push 
1. first time set up local repo to track remote repo
```
git push -u origin {branch_name}
```
2. normal push (local branch newer than remote) 
```
git push
```
3. abnormal push(local branch diverted from remote)
- rebase-fixup | rebase-squash | commit-amend  
```
git push -f 
# only use if is not a shared branch.
```