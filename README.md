# Run
```
docker-compose up -d
```

if elasticsesarch won't up and have error `vm.max_map_count`
run this command for windows:
```
wsl -d docker-desktop

sysctl -w vm.max_map_count=262144
```

# Stop
```
docker-compose stop
```

# Remove
```
docker-compose down
```