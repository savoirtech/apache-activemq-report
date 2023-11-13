# Apache ActiveMQ Report
--- 

Apache ActiveMQ 6.0.0

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  |
|---------------------|-----------|-------|--------------|-------|-------|
| CentOS Stream 9         | IBM Semeru Community Edition 17   | 3.6.3 | PPC64LE      | Success | Nov 12, 2023 |
| MacOS 14.1.1          | Amazon Corretto 17   | 3.9.5 | AArch64      |  Success | Nov 12, 2023 |
| Ubuntu 22.04.3 LTS          | Amazon Corretto 17   | 3.9.5 | x64      | Success | Nov 12, 2023 |
| Ubuntu 22.04.3 LTS          | IBM Semeru Community Edition 17   | 3.9.5 | x64      | Success | Nov 13, 2023 |
| Ubuntu 22.04.3 LTS          | Azul Zulu 21   | 3.9.5 | x64      | Success * | Nov 13, 2023 |


## Errata

IBM Java now returns properties in the same order as other JVMs.
Some unit tests checks for old ordering were disabled.

Azul Zulu 21 build with tests experienced some unit test case failures, and assembly build error. Rebuild with no tests passed.


Quick build to assure compilation. 
```
mvn clean install -DskipTests=true
```

## How to use this repo

Main branch is latest release of Apache ActiveMQ.

A branch is created for each release to record lab results.
