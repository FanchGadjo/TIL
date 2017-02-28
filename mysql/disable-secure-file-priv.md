# Disable mySQL option --secure-file-priv

For error :
```
ERROR 1290 (HY000) at line 72: The MySQL server is running with the --secure-file-priv option so it cannot execute this statement
```

Edit file `/etc/mysql/my.cnf` and add this to `[mysqld]` section.

```
[mysqld]
secure-file-priv = ""
``̀

http://stackoverflow.com/questions/32737478/how-should-i-tackle-secure-file-priv-in-mysql
