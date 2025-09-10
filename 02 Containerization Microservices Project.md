# DevOps on AWS Real Project - All In One

## Containerization Microservices Project

### Dockerfile 

- 
[Install Docker on Ubuntu](https://www.google.com)


### Excute with mongodb 


```sh
iconv -f WINDOWS-1252 -t UTF-8 /app/data/ratings_data.json -o /app/data/ratings_data_utf8.json

mongoimport --host localhost --db test --collection ratings --drop --file /app/data/ratings_data_utf8.json --jsonArray
```
