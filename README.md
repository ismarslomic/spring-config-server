# spring-config-server

## Start

```bash
$ docker volume create --name=spring_config_server_volume
$ docker-compose up
```

Verify that `configServer.status = "UP"` when accessing `http://localhost:58083/management/health`