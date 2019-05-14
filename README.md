### Introduction

This is a standalone mongodb container with populated data.

### Browse your data

Execute the following commands:
```
docker exec -it forest_mongo mongo -u forest -p secret
> use forest_mongo
> db.orders...
```
