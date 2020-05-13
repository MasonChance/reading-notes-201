# SQL (Structured Query Language)

Sequel is the language used to communicate with your database (we will be using postgres). 

SQL commands or action words are conventionally written in all caps.
``` GET
    ADD
    UPDATE
    DELETE
```
# pstgress

Postgress is initiated from your terminal the windows command is `pgstart`  to spin up the database locally then run `psql` to go into the pstgress interface which is indicated by `usrnam$=#`

## Server Setup

the below code snippet uses `<>` to indicate dynamic or user||server-unique information that is put into the code.

```environment
const pg = require('postress')
const client = new pg.Client(<databaseurl *store as an environment variable*>);
client.on('error', console.err); // this will capture the error thrown instead of just throwing an error.

client.connect(<databasename>);

```


