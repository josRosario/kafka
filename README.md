## create the project or start it
* run `docker-compose up`

first step

```javascript
docker pull apache/kafka-native:3.8.0

```
second 

```javascript
$ docker run -p 9092:9092 apache/kafka-native:3.8.0


```

```javascript
kafka-topics.sh \
--create \
--bootstrap-server localhost:9092 \
--replication-factor 1 \
--partitions 1 \
--topic test



```

listar los topis

```javascript
kafka-topics.sh --list --bootstrap-server localhost:9092



```
