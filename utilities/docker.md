# Docker

### Delete image

```text
docker image rm 112r1d
```

### Delete all containers and images

```text
docker ps -a -q | xargs docker rm
docker images -a -q | xargs docker rmi -f
```

