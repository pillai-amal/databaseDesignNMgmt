- create table 
```sql
CREATE TABLE student(
    name VARCHAR(255),
    roll INT,
);
```
- drop table
```sql
DROP TABLE student 
```
- Truncate (keeps table but will remove all the content)
```sql
TRUNCATE TABLE student;
```
- add column 
```sql

ALTER TABLE student ADD (addr VARCHAR(225),phone VARCHAR(10)) 
```
- Remove column
```sql
ALTER TABLE student DROP COLUMN addr;
```
- Rename column
```sql
ALTER TABLE student RENAME COLUMN old_name to new_name;
```
- Delete a specific record 
```sql
DELETE  student WHERE id=3;
```
# Select Statements
```sql
SELECT expressions
FROM tables
WHERE conditions;

//optionals 
GROUP BY
HAVING
ORDER BY
```

 - To eliminate duplicates 
 ```sql   
SELECT DISTINCT expressions
 ```
