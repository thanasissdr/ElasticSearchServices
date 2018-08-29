# INSTRUCTIONS

The main services are `elasticsearch` and `kibana` pulled as images. In order to run them, just
```
docker-compose up
```

## Possible issues: 
If you use Linux, you might need to set up  `vm.max_map_count=262144` in `/etc/sysctl.conf`, otherwise there might be issues when kibana loads, e.g. "No living connections".

## Load data
In order to load some data to play around, just 
```
sh commands_for_uploading_to_elastic.sh
```

