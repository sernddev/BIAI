1. place the java project in src folder
 ex: wren-engine-0.15.1

connect to docker inside
>> docker exec -it -u 0 wren-engine-builder bash

 go to directory of sourccode

run below command
>> mvn clean package -DskipTests -P exec-jar
it should build and generates jars in target folder.