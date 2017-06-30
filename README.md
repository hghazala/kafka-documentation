# kafka-documentation
Play with kafka in console command lines (see https://kafka.apache.org/quickstart).
- Start a ZooKeeper server.
- Start a Kafka server.
- Create a topic.
- Run multiple brokers : 
  * Copy/paste server.properties file and change its content, properties should be updated are: broker.id, listeners (9092 by default)
  and log.dirs.
  * Create a new topic with a replication factor of 3.
  "leader" is the node responsible for all reads and writes for the given partition. Each node will be the leader for a randomly selected portion of the partitions.
