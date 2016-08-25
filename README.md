Example for reading & writing into Hive
==================================

Package for saagie : mvn package and get the package in target.

Usage in local :

 - mvn package
 - java -jar target/example-java-read-and-write-from-hive-1.0-SNAPSHOT-jar-with-dependencies.jar jdbc:hive2://hiveserver:10000/;ssl=false

Usage in Saagie :

 - mvn package (in local, to generate jar file)
 - create new Java Job
 - upload the jar (target/example-java-read-and-write-from-hive-1.0-SNAPSHOT-jar-with-dependencies.jar)
 - copy URL from hive connection details panel and add it in first argument in the command line
 - choose java 8
 - create and launch.
