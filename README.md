# docker-shadowsocks

## use

```
docker run --name shadowsocks-client \
            --restart=always \
            -d \
            -p 1080:1080 \
            -e PASSWORD=KC36f644A194B7a6 \
            shadowsocks-client
```