## [git squash/ fixup] 
## NOTE: first commit cannot be used for squash.
## If only 2 commits on branch, you cannot do a 'rebase'. 
```
git rebase -i HEAD~{num_of_commits}
```
---> editor window as below:
```
- commit 01 -- oldest 
- commit 02 -- older
- commit 03 -- newest
```

---> if squash/fixup desired: 
```
[pick,reword] - commit 01 -- oldest 
[squash, fixup] - commit 02 -- older
[squash, fixup] - commit 03 -- newest
```

 

