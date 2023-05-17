# Lighttpd Container

## Synopsis

Lighttpd Container is a high-performance web server designed for speed, security, and flexibility.

## Running Locally

### Requirements
- Docker

### Building Container Image
```
docker build -t brpedromaia_lighttpd:latest . -f ContainerFile
```

### Running Lighttpd Container Image
```
docker run --rm -it --name brpedromaia_lighttpd -p 4000:4000 brpedromaia_lighttpd:latest
```
