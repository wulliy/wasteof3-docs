Gets all of the information about a post
```
GET /posts/62893ed4c84fe3bebc2c66da/__data.json
```

Gets every post that has reposted a post
```
GET /posts/62893ed4c84fe3bebc2c66da/reposts/__data.json
```

Gets information about a comment on a post
```
GET /posts/63db9751040f988e1c71ea5f/comments/63dbbfda040f988e1c71eabe/__data.json
```

Love/unlove a post
```
POST /posts/62893ed4c84fe3bebc2c66da/loved
```

Post a comment on a post
```
POST /posts/62893ed4c84fe3bebc2c66da/comments
BODY {"content": "<p>comment</p>"}
```

Reply to a comment on a post
```
POST /posts/63db9751040f988e1c71ea5f/comments/63dbbfda040f988e1c71eabe/replies
BODY {"content": "<p>reply</p>"}
```

Delete a comment/reply on a post
```
DELETE /comments/63dbbfda040f988e1c71eabe
```

Create a post (to repost another post, include a "repost" key with the post's id being the value in the body)
```
POST /posts
BODY {"content": "<p>post content here</p>"}
```
