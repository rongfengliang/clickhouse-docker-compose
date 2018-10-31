# clickhouse with docker-compose running

## How to run

```code
docker-compose up -d
```

## access address

```code
http interface http://hostip:8123
for native client connect port 9000
```

## how to Connect server

```code
with docker client

docker run -it yandex/clickhouse-client --host ${serverip|hostip}
```