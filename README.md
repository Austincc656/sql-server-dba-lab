# Microsoft SQL Server DBA Lab

## Project Overview

This repository documents my hands-on Microsoft SQL Server Database Administration lab. The project is designed to simulate a practical server and database environment where I can build experience in Windows Server administration, virtualization, Microsoft SQL Server configuration, database management, security, backup and recovery, troubleshooting, and performance monitoring.

The environment is being developed progressively as part of my practical SQL Server DBA training. The repository will continue to grow as additional administration tasks and database projects are completed.

## Lab Environment

- VMware Workstation 17 Player
- Windows Server 2019 Datacenter Evaluation
- Microsoft SQL Server 2016
- SQL Server Management Studio (SSMS)
- SQL Server Configuration Manager
- SQL Server Database Engine
- SQL Server Agent
- SQL Server Browser
- AdventureWorks sample database for upcoming database exercises

## Current Architecture

```text
Host Computer
└── VMware Workstation
    └── Windows Server 2019 Virtual Machine
        ├── Microsoft SQL Server 2016
        ├── SQL Server Database Engine
        ├── SQL Server Agent
        └── SQL Server Management Studio
```

## SQL Server Storage Configuration

| Purpose | Directory |
|---|---|
| Database Data Files | `C:\SQL_DATA_FILES` |
| Transaction Log Files | `C:\SQL_LOG_FILES` |
| TempDB | `C:\SQL_TEMPDB` |
| Database Backups | `C:\SQL_BACKUPS` |

This layout provides practical experience with separating SQL Server data, transaction logs, TempDB, and backup files in preparation for understanding production database storage architecture.

## Work Completed

- Created and configured a Windows Server virtual machine
- Configured VM memory, processor, storage, and networking resources
- Expanded the virtual disk from approximately 20 GB to 50 GB
- Extended the Windows Server C: volume using Disk Management
- Installed and configured Windows Server 2019
- Installed Microsoft SQL Server 2016
- Installed SQL Server Management Studio
- Configured the default `MSSQLSERVER` instance
- Configured Mixed Mode authentication
- Added the Windows Administrator account as a SQL Server administrator
- Configured dedicated data, log, TempDB, and backup directories
- Configured SQL Server Database Engine and SQL Server Agent services
- Verified SQL Server services using SQL Server Configuration Manager
- Connected successfully to the SQL Server instance through SSMS
- Verified the SQL Server system databases: `master`, `model`, `msdb`, and `tempdb`

## Repository Structure

- [`docs/`](docs/) — Technical documentation and implementation notes
- [`screenshots/`](screenshots/) — Lab evidence and configuration screenshots
- [`sql/`](sql/) — SQL scripts and database exercises
- [`backup-recovery/`](backup-recovery/) — Backup, restore, and recovery exercises
- [`security/`](security/) — Authentication, users, roles, and permissions
- [`performance/`](performance/) — Monitoring and performance optimization exercises

## Skills Demonstrated

Microsoft SQL Server • SQL Server Management Studio • Windows Server 2019 • VMware Workstation • Virtualization • SQL Server Installation & Configuration • Storage Configuration • Authentication • SQL Server Services • Server Administration • Troubleshooting • SQL

## Project Status

**In Progress**

This repository reflects hands-on lab work completed to date. Backup/recovery, security administration, performance tuning, and additional SQL Server administration tasks will be documented as they are completed.
