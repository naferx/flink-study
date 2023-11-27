
### Apache Flink

#### Starting a local cluster
 `$FLINK_HOME/bin/start-cluster.sh`

#### Checking the process
 `ps aux | grep flink`

#### Stopping the cluster
 `$FLINK_HOME/bin/stop-cluster.sh`

#### Submitting a job
 `$FLINK_HOME/bin/flink run $FLINK_HOME/examples/streaming/WordCount.jar --input input/wordcount.txt --output output`

#### Verifying the output
`tail log/flink-*-taskexecutor-*.out`
