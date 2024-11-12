# MySQL User and Permission

## User

Create:
```sql
CREATE USER 'user'@'host' IDENTIFIED BY 'password';
```

Drop:
```sql
DROP USER 'user'@'host';
```

## Permission

Privileges:

> CREATE, ALTER, DROP, INSERT, UPDATE, DELETE, SELECT, REFERENCES, RELOAD

Grant:
```sql
GRANT <privilege> ON <database.table> TO 'user'@'host';
```

Grant All:
```sql
GRANT ALL PRIVILEGES ON *.* TO 'user'@'host' WITH GRANT OPTION;
```

Flush:
```sql
FLUSH PRIVILEGES
```

Revoke:
```sql
REVOKE <type_of_permission> ON <database.table> FROM 'user'@'host';
```

Show:
```sql
SHOW GRANTS FOR 'user'@'host';
```
