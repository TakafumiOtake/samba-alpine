# samba-alpine
docker image for samba using alpine OS.

```shell
docker run -d -p 137-138:137-138/udp -p 139:139 -p 445:445 --name samba --net=host takafumiotake/samba-alpine
```
