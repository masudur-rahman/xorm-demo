# xorm-demo

## Start Postgres Database
```bash
$ # docker rm postgres --force
$ docker run --name postgres -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -e POSTGRES_DB=xorm-demo -p 5431:5432 -d postgres
```
## Run program
```bash
$ go run main.go
```
