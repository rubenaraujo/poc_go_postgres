# Go-Postgres proof-of-concept

This project is simple CRUD application built in golang and using PostgreSQL as DB.

## Pre-requisite
1. Install golang v1.11 or above.
2. A PostGreSQL up and running.
  
## PostgreSQL Table

```sql
CREATE TABLE users (
  userid SERIAL PRIMARY KEY,
  name TEXT,
  age INT,
  location TEXT
);
``` 

