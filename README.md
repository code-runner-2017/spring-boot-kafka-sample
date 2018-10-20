# SpringBoot Kafka Sample

- download kafka from https://kafka.apache.org/downloads

    tar zxvf  kafka_<version>.tgz
    cd kafka_<version>

On Linux:
    ./bin/zookeeper-server-start.sh config/zookeeper.properties
    ./bin/kafka-server-start.sh config/server.properties
    
On windows:
    ./bin/windows/zookeeper-server-start.sh config/zookeeper.properties
    ./bin/windows/kafka-server-start.bat config/server.properties

Run this project from STS (rclick on the project > Run as... > SpringBoot application)
or using gradlew:

    ./gradlew bootRun
