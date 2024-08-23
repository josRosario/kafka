## create the project or start it
* run `docker-compose up -d`


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
