
### Apache Flink

#### starting a local cluster
 `$FLINK_HOME/bin/start-cluster.sh`

#### checking the process
 `ps aux | grep flink`

#### stopping the cluster
 `$FLINK_HOME/bin/stop-cluster.sh`

#### submitting a job
 `$FLINK_HOME/bin/flink run examples/streaming/WordCount.jar`

#### Verifying the output
`tail log/flink-*-taskexecutor-*.out`
