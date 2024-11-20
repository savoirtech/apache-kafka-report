# Apache Kafka Report

Apache Karaf 3.9.0

## System Report

| Operating System    | JDK       | Gradle | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| Ubuntu 22.04 LTS    | Eclipse Adoptium 21  | 8.10.2 | x64      | Success | Nov 20. 2024 | |
| Ubuntu 22.04 LTS    | IBM Semeru 17  | 8.10.2 | x64      | Pending | Nov 20. 2024 |  |
| CentOS Stream 9    | Eclipse Adoptium 17  | 8.8 | PPC64LE      | Success | Nov 20. 2024 |  5 failing tests out of 5901: trogdor,storage,metadata,clients,core  |
| CentOS Stream 9    | IBM Semeru 17  | 8.10.2 | PPC64LE      | Pending | Nov 20. 2024 |    |

## Errata


Fast build to assure compilation. 
```
gradlew jar
gradlew test
```

## How to use this repo

Main branch is latest release of Apache Kafka.

A branch is created for each release to record lab results.
