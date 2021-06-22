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

### See last commit of each file in a directory
```
git ls-tree -r --name-only HEAD | while read filename; do
  echo "$(git log -1 --format="%H %ad" -- $filename) $filename"
done
```
