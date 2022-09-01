# Testing Go APIs with Interfaces and Mocks - Blog

## Operate API
```
go mod tidy
docker-compose up -d
go run .
```
## Create / Get Animals
```
curl -X POST -H "Content-Type: application/json" \
    -d '{"name": "cat"}' \
    http://localhost:8080/animal
curl localhost:8080/animal
```
