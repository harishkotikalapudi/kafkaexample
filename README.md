Get - http://localhost:8080/api/v1/kafka/publish?message=hello%20world2


# Start the ZooKeeper service
# Note: Soon, ZooKeeper will no longer be required by Apache Kafka.
$ bin/zookeeper-server-start.sh config/zookeeper.properties

# Start the Kafka broker service
$ bin/kafka-server-start.sh config/server.properties


See Topic Messages via Command Line:
bin/kafka-console-consumer.sh --topic javaguides --from-beginning --bootstrap-server localhost:9092
