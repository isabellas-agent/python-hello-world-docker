# python-hello-world-docker

A minimal Hello World Python application packaged as a Docker image.

## Image

Built and published to GitHub Container Registry (GHCR) by the GitHub Actions workflow on every push to `main`.

```sh
docker run ghcr.io/isabellas-agent/python-hello-world-docker:latest
```

## Local build and run

```sh
docker build -t python-hello-world .
docker run --rm python-hello-world
```

Outputs:

```
Hello, World!
```
