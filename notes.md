
### Apache Flink

# starting the cluster
    ./bin/start-cluster.sh

# stopping the cluster
    ./bin/stop-cluster.sh

# checking the process
 ps aux | grep flink

# submitting a job
./bin/flink run examples/streaming/WordCount.jar