Get your current message count
```
GET /messages/count
```

Gets all of your messages (an optional `page` argument can be specified)
```
GET /messages/__data.json
```
```
GET /messages/__data.json?page=2
```

Marks all of your messages as read
```
POST /messages/mark-all-as-read
```
