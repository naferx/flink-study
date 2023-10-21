
### Apache Flink

#### starting a local cluster
 `./bin/start-cluster.sh`

#### checking the process
 `ps aux | grep flink`

#### stopping the cluster
 `./bin/stop-cluster.sh`

#### submitting a job
 `./bin/flink run examples/streaming/WordCount.jar`

#### Verifying the output
`tail log/flink-*-taskexecutor-*.out`
