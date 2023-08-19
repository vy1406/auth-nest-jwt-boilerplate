
## Running the app

```bash
# development
$ npm run start
# or 
$ npm run start:dev
```


## Go to postman

Create a route:
localhost:8080/auth/login
Post

Body: (raw, json)

{
    "username": "john",
    "password": "123"
}

you will recieve access_token. copy the value.


Create a route:
localhost:8080/auth/protected
Get
Authorization -> type: Bearer -> paste the value from access_token
you will hit /protected route. 
