# Apache ActiveMQ Report
--- 

Apache ActiveMQ 5.19.0

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  | Notes |
|---------------------|-----------|-------|--------------|-------|-------|-------|
| Ubuntu 22.04 LTS    | Azul Zulu 11   | 3.9.5 | x64      |Failure | March 7, 2025| Build stopped at unit tests java.io.IOException: Failed to start database 'testJdbcConfig' with class loader jdk.internal.loader.ClassLoaders |
| CentOS Stream 9     | IBM Semeru Open Edition 11 | 3.6.0 | PPC64LE      | Failure | March 7, 2025 | Build failure at Http Protocol Support - could not be resolved: org.apache.activemq:activemq-unit-tests:jar |
| Windows 11 Pro      | Eclipse Adoptium 11 | 3.8.5 | x64      |  |  | |


## Errata


## How to use this repo

Main branch is latest release of Apache ActiveMQ.

A branch is created for each release to record lab results.
