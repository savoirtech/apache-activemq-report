# Apache ActiveMQ Report
--- 

Apache ActiveMQ 6.1.4

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  | Notes |
|---------------------|-----------|-------|--------------|-------|-------|-------|
| CentOS Stream 9         | IBM Semeru Community Edition 17   | 3.9.6 | PPC64LE      | Success | Nov 8, 2024 | Several Unit test failures. |
| Ubuntu 22.04.3 LTS          | Amazon Corretto 17   | 3.9.5 | x64      | Success | Nov 8, 2024 |  |
| Ubuntu 22.04.3 LTS          | Eclipse Adoptium 17   | 3.9.5 | x64      | Success | Nov 8, 2024 |  |
| Ubuntu 24.04 LTS          | Bellsoft Liberica 17   | 3.9.5 | AArch64      | Success | Nov 8, 2024 | Unit tests, Http Protocol Support, Web Demo, and Assembly. |
| Ubuntu 24.04 LTS          | IBM Semeru 17   | 3.9.5 | AArch64      | Pending  | Nov 8, 2024 |  |
| Windows 11 Pro          | Eclipse Adoptium 21  | 3.9.5 | x64      | Success  | Nov 8, 2024 | Journal Corruption For Index Recovery Test fails. |
| Windows 11           | Bellsoft 17  | 3.9.5 | AArch64      | Success  | Nov 8, 2024 | Journal Corruption For Index Recovery Test fails. |

## Errata


Quick build to assure compilation. 
```
mvn clean install -DskipTests=true
```

## How to use this repo

Main branch is latest release of Apache ActiveMQ.

A branch is created for each release to record lab results.
