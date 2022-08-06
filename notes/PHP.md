# PHP Syntax

```php
    <?php
        // code goes here
    ?>
```
Example :
```php
    <?php
        $str = "helllo";
        $x=240;
        $y=3.14;
        echo "string is $str";
        echo "number is $x";
        echo "float value is $y";
    ?>
```

# PHP From handling 
## PHP super globals 

- $_GET
-   $_POST

# PHP Sessions
> PHP sessions is used to pass infoirmations from one page to another page. 

> PHP sission creates a unnique suser_ID for each browser and avoid conficts between the browsers

- $_SESSION : is an <i>  associative array <i/> that contains ann session variables. 
    - It is used to set and get session variables.
- session_start()
    - starts a new session is there is no exsisting session otherwise returns the existing serssion.
- session_destroy()
    - Destroys the all session variables.

# PHP Database Connection
- Using mysqli_connect()
    - Functions available are:
        - connect()
        - mysqli_close()
        - fetch_array() : fetches result as an associative array/numeric array/both.
        - mysqli_query() :  used execute a query.
        - prepare() : prepares an sql query for execution.
        - fetch_all() : fetches all result array.
        ---
- Using PDO (php database object)
    - Its an light weight PHP extension.
    - PDO is more flexible and can connect to multiple database in comparison with mysqli_connect
    - Bothb are object orieneted.