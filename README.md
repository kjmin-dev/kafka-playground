# kafka-playground

## Run kafka cluster

```bash
docker-compose up -d
```

## Run kafka-console-producer

```bash
docker exec -it kafka-node-1 kafka-console-producer --topic topic-1 --bootstrap-server localhost:9092
```

## Run kafka-console-consumer

```bash
docker exec -it kafka-node-1 kafka-console-consumer --topic topic-1 --from-beginning --bootstrap-server localhost:9092
```
