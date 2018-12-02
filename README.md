# Spark-Examples
It's a runnable project of Spark-Examples 2.4.0, and we have dealed with the maven dependences, and extended some test cases in ```org.spache.spark.examples.mine``` package.

## Run Examples
1. Clone the repo into InteliJ, and create a maven project
2. Waiting for the processing of maven dependences
3. Add ```-Dspark.master=local[3]``` and other program arguments to the VM options of Application Configuration
4. Run it

## Important points to note
- Add VM options for Spark Streaming or Structured Streaming examples  
  ```-Dspark.master=local[3] -Dspark.sql.shuffle.partitions=1```
