# Microsoft SQL Server DBA Lab

## Project Overview

This repository documents my hands-on Microsoft SQL Server Database Administration lab. The project is designed to simulate a practical server and database environment where I can build experience in Windows Server administration, virtualization, Microsoft SQL Server configuration, database management, security, backup and recovery, troubleshooting, and performance monitoring.

The environment is being developed progressively as part of my practical SQL Server DBA training. This repository will therefore continue to grow as additional administration tasks and database projects are completed.

## Lab Environment

The current environment includes:

- VMware Workstation
- Windows Server 2019 Datacenter Evaluation
- Microsoft SQL Server 2016
- SQL Server Management Studio (SSMS)
- SQL Server Configuration Manager
- SQL Server Database Engine
- SQL Server Agent
- SQL Server Browser
- AdventureWorks sample database

## Current Architecture

Host Computer
    |
    └── VMware Workstation
            |
            └── Windows Server 2019 Virtual Machine
                    |
                    ├── Microsoft SQL Server 2016
                    ├── SQL Server Database Engine
                    ├── SQL Server Agent
                    └── SQL Server Management Studio

## SQL Server Storage Configuration

The SQL Server environment was configured with dedicated directories for different database workloads:

| Purpose | Directory |
|---|---|
| Database Data Files | `C:\SQL_DATA_FILES` |
| Transaction Log Files | `C:\SQL_LOG_FILES` |
| TempDB | `C:\SQL_TEMPDB` |
| Database Backups | `C:\SQL_BACKUPS` |

This structure provides practical experience with separating SQL Server data, transaction logs, TempDB, and backup files in preparation for understanding production database storage architecture.

## Work Completed

- Created and configured a Windows Server virtual machine
- Configured VM CPU, memory, storage, and networking resources
- Expanded virtual disk capacity and extended the Windows Server volume
- Installed and configured Windows Server 2019
- Installed Microsoft SQL Server 2016
- Installed SQL Server Management Studio
- Configured the default SQL Server instance
- Configured Windows and SQL Server authentication using Mixed Mode
- Added the Windows administrator account as a SQL Server administrator
- Configured SQL Server data, log, TempDB, and backup directories
- Configured SQL Server Database Engine and SQL Server Agent services
- Connected successfully to the SQL Server instance through SSMS
- Prepared the environment for database administration exercises

## Repository Structure

- `docs/` — Technical documentation and implementation notes
- `screenshots/` — Evidence and screenshots from the lab environment
- `sql/` — SQL scripts and database exercises
- `backup-recovery/` — Backup, restore, and recovery exercises
- `security/` — Authentication, users, roles, and permissions
- `performance/` — Database monitoring and performance optimization exercises

## Skills Demonstrated

Microsoft SQL Server • SQL Server Management Studio • Windows Server • VMware • Virtualization • SQL Server Installation & Configuration • Database Administration • Storage Configuration • SQL Authentication • Server Administration • Troubleshooting • SQL

## Project Status

**In Progress**

The lab is being expanded progressively as I continue developing practical SQL Server database administration skills.
