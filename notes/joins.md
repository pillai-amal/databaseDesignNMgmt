Types of join:
## - Inner Join
    returns common elements in both tables
```sql
        SELECT column_names(s)
        FROM table1 
        INNER JOIN  table2 
        ON table1.attribute=table2.attribute;
``` 
       
## - Outer Join 

- Left Outer Join
    > Cobines all the elements of the first table and common elements of second table.
    ```sql
        SELECT column_names(s)
        FROM table1
        LEFT JOIN table2
        ON table1.attribute=table2.attribute
    ```

- Right Outer Join
    > Cobines all the elements of the second table and common elements of the first table.
- Full Outer Join
    > combines both the tables when there is match in either one of the table.
    ```sql
        SLECT column_names(s)
        FROM table1
        FULL OUTER JOIN table2
        ON table1.attribute=table2.attribute
        WHERE condition
    ```

## - Cross Join
