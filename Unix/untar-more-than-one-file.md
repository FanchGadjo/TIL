# Find Newer Files

Using `xargs`, because it won't work with a wildcard.

```
$ ls *.tar | xargs -i tar xf {}
```

http://stackoverflow.com/a/583891
