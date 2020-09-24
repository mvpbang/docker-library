```
公司内部生产、测试数据库备份迁移容器
```
# feature
- debian:7
- mongo:3.6  mongo/mongodump/mongoretore/mongoexport/mongoimport
- postgresql:9.6 
- curl/wget
- nc


# docker
- https://hub.docker.com/_/mongo
- https://hub.docker.com/_/postgres

```
mongo:3.6
postgres:9.6-alpine

docker run --name some-mongo -d mongo:3.6
docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres:9.6-alpine
```