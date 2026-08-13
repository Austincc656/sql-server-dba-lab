# Lab Screenshots

This directory contains visual evidence from the Microsoft SQL Server DBA lab. Screenshots are used to document configuration milestones and demonstrate the practical administration work completed in the environment.

## Completed Evidence to Add

The current lab work has produced screenshots covering:

1. **VM storage expansion** — VMware virtual disk configured to 50 GB.
2. **Windows Disk Management** — C: volume extended to use the additional virtual disk capacity.
3. **SQL Server feature selection** — Database Engine Services and supporting SQL Server components selected during setup.
4. **SQL Server instance configuration** — Default `MSSQLSERVER` instance configuration.
5. **SQL Server service configuration** — Database Engine and SQL Server Agent service settings.
6. **Mixed Mode authentication** — Windows and SQL Server authentication configured with the Windows Administrator added as a SQL Server administrator.
7. **SQL Server storage directories** — Dedicated directories configured for data files, transaction logs, TempDB, and backups.
8. **Successful SQL Server installation** — SQL Server 2016 setup completed successfully.
9. **SQL Server Configuration Manager** — Database Engine and SQL Server Agent verified as running.
10. **SSMS connection** — Successful Windows Authentication connection to the SQL Server instance.
11. **SSMS Object Explorer** — SQL Server instance visible with the `master`, `model`, `msdb`, and `tempdb` system databases.

## Suggested File Naming

Use descriptive names when adding screenshots, for example:

```text
01-vm-disk-configuration.png
02-windows-disk-management.png
03-sql-server-feature-selection.png
04-instance-configuration.png
05-service-configuration.png
06-mixed-mode-authentication.png
07-data-directory-configuration.png
08-installation-success.png
09-sql-services-running.png
10-ssms-server-connection.png
11-ssms-object-explorer.png
```

> Screenshots should not expose passwords, credentials, private keys, or other sensitive information.
