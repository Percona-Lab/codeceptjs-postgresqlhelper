# codeceptjs-postgresqlhelper
CodeceptJS helper to execute queries on PostgreSQL database

## Installation

```js
npm i codeceptjs-postgresqlhelper
```

## Configuration

This helper should be configured in `codecept.conf.js`

Example:

```js
{
  //...
   helpers: {
     PostgresqlDBHelper: {
          require: 'codeceptjs-postgresqlhelper',
           host: '127.0.0.1', 
           port: 5432,
           user: 'postgres',
           password: 'postgres',
           database: 'postgres',
        },
  //...
}
```

To use this helper you need to provide the following info:

- `host`: hostname or IP address of the PostgreSQL instance
- `port`: port
- `user`: username
- `password`: password
- `database`: database to which you want to connect
