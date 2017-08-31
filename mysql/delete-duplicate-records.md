# Delete duplicate records
```
ALTER IGNORE TABLE `TableA`   
ADD UNIQUE INDEX (`member_id`, `quiz_num`, `question_num`, `answer_num`);
```

https://stackoverflow.com/questions/14046355/how-do-i-delete-all-the-duplicate-records-in-a-mysql-table-without-temp-tables

https://stackoverflow.com/questions/36647058/removing-duplicates-with-unique-index

http://www.stetsenko.net/2010/08/mysql-how-to-force-a-new-unique-index-to-drop-duplicated-rows/
