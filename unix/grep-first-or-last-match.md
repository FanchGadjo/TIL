# Grep first or last match

## Grep first
```
grep -m 1 "pattern1"

```

http://stackoverflow.com/questions/14093452/grep-only-the-first-match-and-stop
http://stackoverflow.com/questions/19096014/how-to-grep-for-the-first-instance-of-the-pattern-among-multiple-patterns

# Grep last
Using `tac` to reverse-print the file before `grep`. Pipe into another `tac` to re-reverse file, if using `grep -A`, `-B` or `-C`.

```
tac test.txt | grep -m 1 "pattern1" | tac
``̀


