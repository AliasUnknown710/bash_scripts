# Automation Scripts

Automated system administration tasks including backups, log archiving, git synchronization, and scheduled job management.

## Overview

This directory contains scripts designed to automate routine system administration tasks, reducing manual effort and improving consistency.

## Quick Start

```bash
chmod +x *.sh
./Auto_Backup.sh
```

## Scripts

| Script | Purpose |
|--------|---------|
| [Archive_Logs.sh](Archive_Logs.sh) | Automatically archive log files for storage optimization |
| [Auto_Backup.sh](Auto_Backup.sh) | Create scheduled automated backups |
| [Cron_Audit.sh](Cron_Audit.sh) | Audit and verify cron job configurations |
| [Cron_Job_Linter.sh](Cron_Job_Linter.sh) | Validate and lint cron job syntax |
| [Extract_Archives.sh](Extract_Archives.sh) | Extract compressed archives with error handling |
| [Git_Auto_Pull.sh](Git_Auto_Pull.sh) | Automatically pull updates from git repositories |
| [Installer.sh](Installer.sh) | Automated installation script for dependencies |
| [Syslog_Forwarder.sh](Syslog_Forwarder.sh) | Forward system logs to remote syslog servers |

## Common Usage

Each script in this directory can be executed directly:

```bash
./Archive_Logs.sh
```

For more detailed information about each script, refer to the individual README files in this directory.

## Requirements

- Bash 4.0+
- Standard GNU utilities (sed, awk, grep, etc.)
- Appropriate system permissions for the tasks being automated

## License

MIT License - See [LICENSE](../LICENSE) for details
