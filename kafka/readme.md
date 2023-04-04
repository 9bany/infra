## Docker exec

```
 docker exec -it <container_id> /bin/bash
```
 
## Producer

```
 kafka-console-producer --broker-list localhost:9092 --topic <topic_name>
```

## Consumer

```
kafka-console-consumer --topic <topic_name> --bootstrap-server broker:9092 --from-beginning
```

## CLI Tool

- Kaf: https://github.com/birdayz/kaf