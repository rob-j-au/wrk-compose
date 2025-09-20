## wrk-compose

This is a docker-compose file for running the wrk-book, wrk-ork and app-node services with prometheus and grafana monitoring.

- https://github.com/rob-j-au/wrk-book
- https://github.com/rob-j-au/wrk-ork
- https://github.com/rob-j-au/app-node





### Usage

Create Configuration

```
./setup-config.sh
```

Configure Environment

```
/env/wrk-book.env
/env/wrk-ork.env
/env/app-node.env
```


Start Compose Stack

```
docker compose up -d
```

View Logs

```
docker compose logs wrk-book
docker compose logs wrk-ork
docker compose logs app-node
```

Stop Compose Stack

```
docker compose down
```

