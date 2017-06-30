# NodeJs Image for develope

This image is for building your dependencies. You should use
chanhw/node to run them (smaller image).

## Using

```sh
docker run --rm -v "$PWD":/app -w /app chanhw/node:dev npm install
```


## Building this image

```sh
docker build -t chanhw/node:dev --no-cache .
```

Tag it with Alpine nodejs version, run `docker run --rm chanhw/node:dev node -v` to check version.

```sh
docker tag chanhw/node:dev chanhw/node:X.Y.Z-dev
```

Push:

```sh
docker push chanhw/node
```