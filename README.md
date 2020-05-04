# flink-examples
Playing with apache flink. 

# INSTALLATION

1- Follow instructions on flink [site.](https://flink.apache.org/downloads.html) 

# RUNNING

To be able to run the java files, we should be able to first start the flink server.

Simply type ``bin/start-local.sh`` in your terminal where the flink folder located in. Or ``bin\start-local.bat`` in windows os.

Build your artifact jar with maven. Move jar file to the where flink folder located in.
Then type the command:

``bin\flink run -c com.guzelcihad.examples.FilterStrings flink-examples-1.0-SNAPSHOT.jar`` 

in your teminal to submit a job to the task manager. 

Go to flink [dashboard](http://localhost:8081/#/overview) in your local to be able to see the running jobs in browser.


