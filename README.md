#### Server

 * Express server

#### Queries

```
curl -X POST \
-H "Content-Type: application/json" \
-d '{"query": "{ hello }"}' \
http://localhost:4000/graphql
```

#### GraphQL clients

[Relay](http://graphql.org/graphql-js/graphql-clients/) - "can automatically handle batching, caching"
