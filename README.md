# Zniszcz-Auth
Simple JWT Authorisation Micro-Service

## Installation
1. Install dependencies

``` 
$ npm install
```

2. Copy config files
```
$ cp ./config/config.json.dist ./config/config.json
$ cp ./config/crypto.json.dist ./config/crypto.json
```

3. Fill correct connection data and crypto info (salt for storing passwords, secret for JWT and JWT token expiration).

4. Run migration
```
$ ./node_modules/.bin/sequelize db:migrate
```

5. Run seeds
```
$ ./node_modules/.bin/sequelize db:seed:all
```

6. Run app
```
$ npm start
```
