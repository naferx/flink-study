A Flink application project using Scala and SBT.

To run and test your application use SBT invoke: 'sbt run'

In order to run your application from within IntelliJ, you have to select the classpath of the 'mainRunner' module in the run/debug configurations. Simply open 'Run -> Edit configurations...' and then select 'mainRunner' from the Use classpath of module dropbox.

`sbt package`

`$FLINK_HOME/bin/flink run -c org.example.WordCount target/scala-2.12/flink_2.12-0.1.jar`