# How to start the Express.js API in order for it to work correctly

- Install Node.js
- Run `npm install`
- Go to the main directory and run `nodemon index.js`

# Setting up the PostgreSQL database in your local environment

- Download PostgreSQL v13.2: https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
- Go with the default installation, for the database superuser password choose `wie123` and default port `5432`
- When you get to the Stack Builder window just close it and search for the `pgAdmin 4` app, it will open the database's UI.
- There in the _Databases_ section create a new database named `WIEProject`
- You can create the `movietable` table using the query in _data/movie_table_creation_sql.txt_ file
- Then refresh the `Tables` section, right-click on the created table and import the _data/movie_data.csv_ file
- You can create the `users` table using the query in _data/users_table_creation_sql.txt_ file
- You can create the `comments` table using the query in _data/comment_table_creation_sql.txt_ file
