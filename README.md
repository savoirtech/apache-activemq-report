# Apache ActiveMQ Report
--- 

Apache ActiveMQ 5.19.0

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  | Notes |
|---------------------|-----------|-------|--------------|-------|-------|-------|
| MacOS 15.3    | Azul Zulu 17   | 3.9.5 | AArch64      |  | March 7, 2025 | Unit test failure AdvisoryTempDestinationTests.testMessageExpiredAdvisory - can not build unit tests jar |
| Ubuntu 22.04 LTS    | Azul Zulu 11   | 3.9.5 | x64      |  |  | Multiple Unit test failures, AMQP, All Jar bundle, and assembly test. |
| Ubuntu 22.04 LTS    | IBM Semeru 17  | 3.9.5 | x64      |  |  | Partition Manager, Unit tests, and assembly test. |
| CentOS Stream 9     | IBM Semeru Open Edition 11 | 3.6.0 | PPC64LE      |  |  | Partition Management, Unit Tests, Web Demo, and Assembly had test case failures |
| Windows 11 Pro      | Azul Zulu 17 | 3.8.5 | x64      |  |  | Tests stalled after failed JournalArchieveTest testRecoveryOnArchieveFailure - JournalCorruptionEofIndexRecoveryTest  |
| Windows 11 Pro      | IBM Semeru 17 | 3.8.5 | x64      |  |  | Tests stalled after failed JournalArchieveTest testRecoveryOnArchieveFailure - JournalCorruptionEofIndexRecoveryTest |
| Windows 11       | Bellsoft Liberica 17 | 3.9.8 | AArch64      |  |  | Tests stalled after failed JournalArchieveTest testRecoveryOnArchieveFailure - JournalCorruptionEofIndexRecoveryTest |


## Errata


## How to use this repo

Main branch is latest release of Apache ActiveMQ.

A branch is created for each release to record lab results.
