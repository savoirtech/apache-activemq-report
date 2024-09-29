# Apache ActiveMQ Report
--- 

Apache ActiveMQ 5.18.6

## System Report

| Operating System    | JDK       | Maven | Architecture | Build | Date  | Notes |
|---------------------|-----------|-------|--------------|-------|-------|-------|
| MacOS 14.6.1          | Azul Zulu 17   | 3.9.5 | AArch64      |  |  |  |
| MacOS 14.6.1          | Azul Zulu 11   | 3.9.5 | AArch64      |  |  |  |
| MacOS 14.6.1          | Eclipse Adoptium 11   | 3.9.5 | AArch64      | Failure | Sept 29, 2024 | Multiple Unit test failures, AMQP, All Jar bundle, and assembly test. |
| Ubuntu 22.04 LTS    | Azul Zulu 11   | 3.9.5 | x64      | Success | Sept 29, 2024 | Few unit test failurs in ActiveMQ: Unit Tests and Web Demo. Build completed in 3:52h |
| CentOS Stream 9     | IBM Semeru Open Edition 11 | 3.6.0 | PPC64LE      | Pending | Sept 29, 2024 |  |
| Windows 11 Pro      | Azul Zulu 17 | 3.8.5 | x64      | Failure | Sept 29, 2024 | Tests stalled on JournalArchieveTest testRecoveryOnArchieveFailure |
| Windows 11 Pro      | IBM Semeru 17 | 3.8.5 | x64      | Failure | Sept 29, 2024 | Tests stalled on JournalArchieveTest testRecoveryOnArchieveFailure |
| Windows 11       | Bellsoft Liberica 11 | 3.9.8 | AArch64      |  |  |  |


## Errata


## How to use this repo

Main branch is latest release of Apache ActiveMQ.

A branch is created for each release to record lab results.
