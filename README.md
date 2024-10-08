# Apache Kafka Report

Apache Karaf 3.8.0

## System Report

| Operating System    | JDK       | Gradle | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| Ubuntu 22.04 LTS    | Eclipse Adoptium 17  | 8.10.2 | x64      | Success | Oct 8. 2024 | 1 Failed Test kafka.coordinator.transaction.ProducerIdManagerTest |
| Ubuntu 22.04 LTS    | IBM Semeru 17  | 8.10.2 | x64      | Success | Oct 8. 2024 | 5 Failed Test org.apache.kafka.clients.consumer.internals |

## Errata


Fast build to assure compilation. 
```
gradlew jar
gradlew test
```

## How to use this repo

Main branch is latest release of Apache CXF.

A branch is created for each release to record lab results.
