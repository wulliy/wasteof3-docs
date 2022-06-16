Gets the count of how many users have registered an account on wasteof.money
```
GET /users/
```

Get an user's profile information as JSON
```
GET /users/jeffalo/__data.json
```

Get an user's profile picture (This will redirect to the [prod API site](https://api.wasteof.money))
```
GET /users/jeffalo/picture
```

Get an user's banner (This will also redirect)
```
GET /users/jeffalo/banner
```

Edit an user's sidebar
```
PUT /users/jeffalo/sidebar
BODY [insert body here aaaa]
```

Edit an user's profile color
```
POST /users/jeffalo/color
BODY {"color": "yellow"}
```

??
```
GET /users/jeffalo/admin/__data.json
```
