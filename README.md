# Run
```
cd <app>
docker-compose up -d
```

# Stop
```
docker-compose stop
```

# Remove
```
docker-compose down -v
```

# Error notes
## Elasticsearch
### Windows
if elasticsesarch won't up and have error `vm.max_map_count`
run this command:
```
wsl -d docker-desktop

sysctl -w vm.max_map_count=262144
```