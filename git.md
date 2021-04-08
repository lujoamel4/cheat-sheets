### delete branch locally
```
git branch -d localBranchName
```

### delete branch remotely
```
git push origin --delete remoteBranchName
```

### show staged changes
```
git diff --cached
```

### Set the cache to timeout after 1 hour (setting is in seconds)
```
git config --global credential.helper 'cache --timeout=3600'
```
