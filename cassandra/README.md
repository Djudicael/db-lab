 nodetool status

docker exec -ti cassandra cqlsh <ip> <port> -u cassandra -p cassandra


 user: cassandra password cassandra



nodetool info -h <ip>
nodetool ring



CREATE KEYSPACE BIGCASSANDRA WITH replication = {'class': 'SimpleStrategy', 'replication_factor':3};

SELECT * FROM system_schema.keyspaces ;

ALTER KEYSPACE bigcassandra WITH replication = {'class': 'SimpleStrategy', 'replication_factor':3} and durable_writes = false;

use bigcassandra ;