- go get .
- go run 
- go build
- go test
- ./hello

```azure
 curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```


```azure
curl http://localhost:8080/albums \
    --header "Content-Type: application/json" \
    --request "GET"
```

````azure
curl http://localhost:8080/albums/2
````