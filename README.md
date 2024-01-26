# simple-jwt
Simple implementation of jwt-authorization | react, vite, node.js, postgreSQL

for testing it in your env need to add in your api folder:  
1. db.js
```
import pg from "pg";

const pool = new pg.Pool({
  user: "your acc name",
  password: "your password",
  host: "your host",
  port: "your port",
  database: "db name",
});

export default pool;
```

https://node-postgres.com/apis/pool

2. .env
```
PORT=***port***
CLIENT_URL=***url***
ACCESS_TOKEN_SECRET=***any secret phrase***
REFRESH_TOKEN_SECRET=***any secret phrase***

```


*this project was made with lesson:
https://www.youtube.com/watch?v=-DXdktU-NNg
