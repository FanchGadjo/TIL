# Find biggest files

Find biggest files in a directory (recursively), order them by size and print human-readable sizes.

```
find . -type f -printf "%s\t%p\n" | sort -n | tail -10 | cut -f 2 | xargs -i ls -lahS {} | tac | cut -d' ' -f 5,8
```
