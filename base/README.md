
This image is a base image for tiny images. Currently, it's just the alpine OS image.

## Building this image

First, be sure to get the latest alpine:

```sh
docker pull alpine
docker pull alpine:edge
```

Then build it:

```sh
docker build -t chanhw/base:latest --no-cache .
```

Tag it with Alpine version, run `docker run --rm chanhw/base cat /etc/os-release` to check version.

```sh
docker tag chanhw/base:latest chanhw/base:X.Y.Z
```

Push:

```sh
docker push chanhw/base
```
