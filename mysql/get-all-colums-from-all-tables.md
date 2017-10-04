# Get all columns from all MySQL tables


```
select TABLE_NAME, COLUMN_NAME, COLUMN_TYPE, COLUMN_KEY from information_schema.columns where table_schema = 'my_db' order by table_name,ordinal_position;
```

https://stackoverflow.com/questions/5648420/get-all-columns-from-all-mysql-tables
