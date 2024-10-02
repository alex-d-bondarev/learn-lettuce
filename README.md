# learn-lettuce

## Tests

## Manual

### Setup

per https://hub.docker.com/r/redis/redis-stack

```shell
docker run -v ./local-data/:/data -d --name redis-stack -p 6379:6379 -p 8001:8001 -e REDIS_ARGS="--requirepass mypassword" redis/redis-stack:latest
```

Use CLI after `docker exec -it redis-stack redis-cli` and/or open [Local RedisInsight](http://localhost:8001)
