# Replace string over multiple files
``` 
cd /path/to/your/folder
sed -i 's/foo/bar/g' *
```
Occurrences of "foo" will be replaced with "bar".


```
find ./ -type f -exec sed -i 's/string1/string2/g' {} \;
```
To avoid error due to folders among the files.
