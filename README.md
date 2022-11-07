# WriteupScript
go script for check writeups in medium then add to database and send it to discord server or telegram.

## Setup
- PostgreSQL
1. Add `writup` database with `postgres` user.
2. Add Your Webhook Disocrd `webhook` or Telegram `Token` & `ChatID`.
3. for Schedule Runing Script You Can use `crontab` in linux.
Example for runing every 3 hours:
```
 0 */3 * * * cd ~/path/WriteupScript/;/usr/bin/go run main.go
```

## Requirements
- go Version 1.19
- Postgrsql
```shell
go mod download github.com/lib/pq
go get github.com/ilyakaznacheev/cleanenv@v1.4.0
```