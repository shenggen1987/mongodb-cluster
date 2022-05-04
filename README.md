# mongodb-cluster


openssl rand -base64 756 > auth.key


```
docker build -t mongo-replset .
```

```
mongo mongodb://root:123@mongo-1:27011/admin --eval 'rs.initiate({ _id: "rs", members: [{_id:1,host:"mongo-1:27011"},{_id:2,host:"mongo-2:27012"},{_id:3,host:"mongo-3:27013"}]})'
```

```
docker-compose up -d

```
