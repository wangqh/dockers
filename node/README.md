# NodeJs alpine Image

Docker Hub: https://hub.docker.com/r/chanhw/node/

## Using

```sh
docker run -it --rm chanhw/node node -v
```

## Building this image

```sh
docker build -t chanhw/node:latest --no-cache .
```

Tag it with Alpine nodejs version, run `docker run --rm chanhw/node node -v` to check version.

```sh
docker tag chanhw/node:latest chanhw/node:X.Y.Z
```

Push:

```sh
docker push chanhw/node
```
