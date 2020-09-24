FROM mongo:3.6 AS builder

FROM ubuntu:xenial
MAINTAINER mvpbang@163.com
COPY --from=builder /usr/bin/mongo /usr/bin/mongodump /usr/bin/mongorestore /usr/bin/mongoexport /usr/bin/mongoimport /usr/bin/
#COPY --from=builder /lib/x86_64-linux-gnu/* /lib/
ENTRYPOINT tail -F /dev/null

```
/ # mongo --version
mongo: error while loading shared libraries: libcrypto.so.1.0.0: cannot open shared object file: No such file or directory
/ # ls -l /usr/lib

docker pull postgres:9.6-alpine
```