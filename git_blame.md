# Ignore a commit in git blame

```
git blame --ignore-rev <commit-id> <file>
```

Example:

```
git blame --ignore-rev 5cc9235d47271127f640fbc565ca7604e2db7d67 ./web/__init__.py
```

# Permanently ignore a commit in git blame

Create new file `.git-blame-ignore-revs` and add the commit-id in the file.

```
git config --local blame.ignoreRevsFile .git-blame-ignore-revs
```


Refer: https://michaelheap.com/git-ignore-rev/
