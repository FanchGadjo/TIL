# Delete tag

You just need to push an 'empty' reference to the remote tag name:
```
git push origin :tagname
```
Or, more expressively, use the `--delete` option:
```
git push --delete origin tagname
```
If you also need to delete the local tag, use:
```
git tag --delete tagname
```

http://stackoverflow.com/questions/5480258/how-to-delete-a-git-remote-tag
