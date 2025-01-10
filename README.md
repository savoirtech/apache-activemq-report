# Apache ActiveMQ Report
--- 

Apache ActiveMQ 6.1.5

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  | Notes |
|---------------------|-----------|-------|--------------|-------|-------|-------|
| CentOS Stream 9         | IBM Semeru Community Edition 17   | 3.9.6 | PPC64LE      | Pending | Jan 10, 2025 | |
| Ubuntu 22.04.3 LTS          | Eclipse Adoptium 17   | 3.9.5 | x64      | Success | Jan 9, 2025 |  |
| Ubuntu 22.04.3 LTS          | Amazon Corretto 17   | 3.9.5 | x64      | Pending | Jan 10, 2025 |  |
| Ubuntu 24.04 LTS          | Bellsoft Liberica 17   | 3.9.5 | AArch64      | Success | Jan 10, 2025 | Unit tests, Http Protocol Support, All Jar Demo, and Assembly. |
| Ubuntu 24.04 LTS          | Eclipse Adoptium 17    | 3.9.5 | x64      | Success  | Jan 9, 2025 | Some tests failed with Bind errors |
| MacOS 15.2          | Eclipse Adoptium 17   | 3.9.9 | AArch64      | Pending | Jan 10, 2025 |  |
| Windows 11 Pro          | IBM Semeru 17  | 3.9.5 | x64      |  Success | Jan 9, 2025 | Failed Journal Recovery Test |
| Windows 11           | IBM Semeru 21  | 3.9.5 | AArch64      | Pending  | Jan 10, 2025 | |
| Windows 11           | Bellsoft Liberica 17  | 3.9.5 | AArch64      | Success  | Jan 9, 2025 | Failed Journal Recovery Test |


## Errata


Quick build to assure compilation. 
```
mvn clean install -DskipTests=true
```

## How to use this repo

Main branch is latest release of Apache ActiveMQ.

A branch is created for each release to record lab results.
