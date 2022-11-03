# WriteupScript
go script for check some medium user and tags then add to database and send it to discord server.

## Setup
- PostgreSQL
1. Add `writup` database with `postgres` user.
2. Add Your Webhook Disocrd `webhook`. 

## Requirements
- go Version 
- Postgrsql
```shell
go mod download github.com/lib/pq
go get github.com/ilyakaznacheev/cleanenv@v1.4.0
```