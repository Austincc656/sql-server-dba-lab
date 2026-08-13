# SQL Server DBA Lab – Screenshots

This directory contains visual evidence from the Microsoft SQL Server DBA lab. The screenshots document the configuration and administration tasks completed while building the environment.

## 01. VMware Virtual Machine Configuration

![VMware VM Configuration](01-vmware-vm-configuration.png)

Configured the Windows Server 2019 virtual machine in VMware Workstation with the memory, processor, storage, and networking resources required for the SQL Server lab.

## 02. Virtual Disk Capacity Expansion

![Virtual Disk Expansion](02-virtual-disk-expansion.png)

Expanded the virtual machine disk capacity to provide sufficient storage for Windows Server, SQL Server, SQL Server Management Studio, and database files.

## 03. Windows Server Storage Management

![Windows Disk Management](03-windows-disk-management.png)

Extended the Windows Server C: volume using Disk Management so that the operating system could use the additional virtual disk capacity.

## 04. SQL Server Feature Selection

![SQL Server Feature Selection](04-sql-server-feature-selection.png)

Selected the SQL Server Database Engine and supporting components required for the database administration environment.

## 05. SQL Server Instance Configuration

![SQL Server Instance Configuration](05-sql-server-instance-configuration.png)

Configured Microsoft SQL Server using the default `MSSQLSERVER` instance for the lab environment.

## 06. Database Engine Authentication

![SQL Server Authentication](06-sql-server-authentication.png)

Configured Mixed Mode authentication to support both Windows Authentication and SQL Server Authentication, with the Windows Administrator account added as a SQL Server administrator.

## 07. SQL Server Storage Architecture

![SQL Server Storage Directories](07-sql-server-storage-directories.png)

Configured dedicated directories for database data files, transaction log files, TempDB, and backups:

- `C:\SQL_DATA_FILES`
- `C:\SQL_LOG_FILES`
- `C:\SQL_TEMPDB`
- `C:\SQL_BACKUPS`

This provides practical experience with organizing SQL Server storage in preparation for understanding production database file architecture.

## 08. Successful SQL Server Deployment

![SQL Server Installation Success](08-sql-server-installation-success.png)

Completed the Microsoft SQL Server 2016 installation successfully, with the selected SQL Server components deployed without installation failures.

## 09. SQL Server Service Management

![SQL Server Services](09-sql-server-services.png)

Verified the SQL Server Database Engine and SQL Server Agent services as running through SQL Server Configuration Manager. SQL Server Browser remained stopped because the lab uses the default SQL Server instance.

## 10. SSMS Connected to SQL Server Instance

![SSMS Connected Instance](10-ssms-connected-instance.png)

Successfully connected SQL Server Management Studio to the SQL Server instance using Windows Authentication and verified access to the core SQL Server system databases:

- `master`
- `model`
- `msdb`
- `tempdb`

## Skills Demonstrated

These screenshots provide evidence of hands-on experience with VMware virtualization, Windows Server storage administration, Microsoft SQL Server installation and configuration, authentication, SQL Server storage configuration, SQL Server services, and SQL Server Management Studio connectivity.

> All screenshots in this repository are from a personal training lab and are intended only to demonstrate practical database administration learning. Sensitive credentials and passwords are not included.
