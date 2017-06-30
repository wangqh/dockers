# Nginx alpine Image

Docker Hub: https://hub.docker.com/r/chanhw/nginx/

## Using

```sh
docker run -it --rm chanhw/nginx nginx -v
```

## Building this image

```sh
docker build -t chanhw/nginx:latest --no-cache .
```

Tag it with Alpine nginx version, run `docker run --rm chanhw/nginx nginx -v` to check version.

```sh
docker tag chanhw/nginx:latest chanhw/nginx:X.Y.Z
```

Push:

```sh
docker push chanhw/nginx
```
