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
- Logstash (Input from random longlat )
- Kibana (for display data)
