# Calling-APIs-from-postgresql
In PostgreSQL, the http extension is used to provide HTTP-related functionality, enabling PostgreSQL to interact with HTTP services directly from within the database. With this extension, you can make HTTP requests, such as GET or POST requests, from within SQL queries.


### This installs the common PostgreSQL extensions, including http.
```bash
sudo yum install postgresql-contrib
```

- Enable the extension in your database: Once the package is installed, connect to your database and create the extension with this SQL command:

```sql
