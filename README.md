# Apache ActiveMQ Report
--- 

Apache ActiveMQ 6.1.6

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  | Notes |
|---------------------|-----------|-------|--------------|-------|-------|-------|
| CentOS Stream 9         | IBM Semeru Community Edition 17   | 3.9.6 | PPC64LE      | Success | March 7, 2025 | A few unstable unit tests. |
| Ubuntu 22.04.3 LTS          | Amazon Corretto 17   | 3.9.5 | x64      | Success | March 7, 2025| Errors in AMQP, All Jar Bundle, Web Demo, and Assembly |
| Ubuntu 24.04 LTS          | Bellsoft Liberica 17   | 3.9.5 | AArch64      | Success  | March 10, 2025 | HTTP Protocol Unit test failure. |
| Ubuntu 24.04 LTS          | IBM Semeru 17   | 3.9.5 | AArch64      |Success  | March 10, 2025| Failed unit tests: MBeanWithAuditLog, TopicSubscriptionInFlightMessageSizeTest, UsageBlockedDispatchTest |


## Errata


Quick build to assure compilation. 
```
mvn clean install -DskipTests=true
```

## How to use this repo

Main branch is latest release of Apache ActiveMQ.

A branch is created for each release to record lab results.
