# nodebird
webp20 twitter clone project

config.json

```json
{
  "development": {
    "username": "root",
    "password": "비밀번호",
    "database": "nodebird",
    "host": "127.0.0.1",
    "dialect": "mysql",
    "operatorAliases": false
  },
  "test": {
    "username": "root",
    "password": null,
    "database": "database_test",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },
  "production": {
    "username": "root",
    "password": null,
    "database": "database_production",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}

```

.env

```sh
COOKIE_SECRET=nodebirdsecret
NODE_ENV=development
```

# create db

```
npx sequelize db:create
```

# run

```
npm run start
```
