# nginx

```bash
docker pull nginx:1.25.4
```

```bash
docker run -d --name webserver -p 80:80 nginx:1.25.4
```

## build

```bash
docker build --platform linux/amd64 -t eorjs37/nginx-webserver:1.0 .
```

## run

```bash
docker run --name=nginx-webserver -d -p 80:80 eorjs37/nginx-webserver:1.0
```

## hub push

```bash
docker push eorjs37/nginx-webserver:1.0
```
