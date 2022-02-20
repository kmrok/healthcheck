# healthcheck

## run

```sh
$ docker build -t healthcheck .
$ docker run -p 80:80 --rm healthcheck
```

## push

```sh
$ docker tag healthcheck:latest ${REPOSITORY}:latest
$ docker push ${REPOSITORY}:latest
```
