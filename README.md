# ELK docker-compose

## Requirement:
- Install docker
- install docker-compose

## How To Run

```sh
docker-compose up -d
```
Open : localhost:5601

## What inside?
- Elasticsearch (3 node for cluster)
- NGINX (as load-balancer to nodes)
- Logstash (Input from API : https://randomuser.me/api/ )
- Kibana (for display data)
