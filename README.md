# ExcelRecordReader
excel input format reader for hadoop

Check the file in src/test/resources/Sample.xlsx for a demo file

1. Clone the project in any directory
2. Navigate to the directory and use the command 'mvn clean install' to create the required jars.
3. Include the jar file ExcelRecordReaderMapReduce-0.0.1-SNAPSHOT-jar-with-dependencies.jar in your environment.

You may test the jar using the command
hadoop jar ExcelRecordReaderMapReduce-0.0.1-SNAPSHOT-jar-with-dependencies.jar input_directory output_directory

After the job has completed, check the output created on HDFS