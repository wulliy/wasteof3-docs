Get an user's profile information as JSON
```
GET /users/jeffalo/__data.json
```

Get an user's profile picture (a redirect to the [wasteof2 api site](https://api.wasteof.money))
```
GET /users/jeffalo/picture
```

Get an user's banner (another redirect)
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
