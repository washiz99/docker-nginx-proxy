# docker-nginx-proxy
Reverse proxy with nginx

- docker 19.03.5
- docker-compose 1.24.0
- openssl 1.1.1


## Instration

```
$ docker clone https://github.com/washiz99/docker-nginx-proxy.git
$ cd docker-nginx-proxy
$ docker-compose build
```

## Usage

### Start

```
$ docker-compose up -d
```

### Terminate

```
$ docker-compose down
```

### create ssl

```
$ cd reverse-proxy/certs
$ openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout ssl.key -out ssl.crt
```

