# maltyxx/docker-curl

## About

[CURL](https://github.com/curl/curl) Docker image based on Alpine Linux.<br />
If you are interested, [check out](https://hub.docker.com/r/maltyxx/) my other 🐳 Docker images!

## Docker

### Supported multi architectures

- armv7 (arm32)
- armv8 (arm64)
- amd64 (x86_64)

## Use this image

### Command line

You can also use the following minimal command :

```bash
docker run --name curl maltyxx/curl:latest curl -s --http2 -I https://www.google.com
```
