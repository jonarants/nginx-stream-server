# Instrucciones para creacion del contenedor

## Contenedor creado

```bash
docker build -t nginx:v1 .
```

```bash
docker run -d -p 1935:1935 -p 80:80 -p 8080:8080 --name nginx nginx:v1
```

```bash
rtmp://localhost/live
```

```bash
http://localhost:8080/hls/test.m3u8
```