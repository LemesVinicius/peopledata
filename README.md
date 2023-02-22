# PeopleData API with Express

> This is an api

## Installation Instructions

```bash
npm install
```

### To run the application

```bash
npm start
```

### To run the tests

```bash
npm test
```

## Routes

### Save a new user

`POST /users`

### Body
    {
        "name":"vinicius",
        "age": 29
    }

### Response

    200 OK
    msg: "usuario salvo"

### Get all users

`GET /users`

### Response

    200 OK
    msg: "usuario salvo"


