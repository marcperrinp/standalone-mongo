### Introduction

This is a standalone mongodb container with populated data.

### Browse your data

Execute the following commands:
```
docker exec -it forest_mongo mongo -u forest -p secret
> use forest_mongo
> db.orders...
```

OR

```
docker exec -it forest_mongo mongo -u forest -p secret --databaseAuthentication=admin forest_mongo
> db.orders...
```

OR

```
docker exec -it forest_mongo mongo mongodb://forest:secret@localhost:27017/forest_mongo?authSource=admin
> db.orders...
```
