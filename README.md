# Arival Bank Test

## Requirements 
- Docker
- Docker compose
## Running Docker Compose file
```
docker-compose up -d --force-recreate
```
## Verify running app:
```
docker ps
```
ensure that all the nodejs, loki, promtail and grafana services are up.

## Accessing nodejs apps:
```
http://0.0.0.0:5001/
```
## Accessing loki api metrics:
```
http://localhost:3100/metrics
```

## Accessing grafana dashboard:
```
http://localhost:3000/login
```

## Running 'Simple script'
```python
python3 WordCounter.py
```