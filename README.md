# Apache ActiveMQ Report
--- 

Apache ActiveMQ 6.1.0

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  |
|---------------------|-----------|-------|--------------|-------|-------|
| CentOS Stream 9         | IBM Semeru Community Edition 17   | 3.6.3 | PPC64LE      |  |  |
| Ubuntu 22.04.3 LTS          | Bellsoft 17   | 3.9.5 | x64      | Success | March 7, 2024 |
| Ubuntu 22.04.3 LTS          | Amazon Corretto 17   | 3.9.5 | x64      | Success | March 13, 2024 |



## Errata


Quick build to assure compilation. 
```
mvn clean install -DskipTests=true
```

## How to use this repo

Main branch is latest release of Apache ActiveMQ.

A branch is created for each release to record lab results.
