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
