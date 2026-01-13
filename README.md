# Bash Scripts Collection

A comprehensive collection of Bash scripts for system administration, automation, maintenance, security hardening, and penetration testing.

## Table of Contents

- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [Installation](#installation)
- [Scripts](#scripts)
- [Usage](#usage)
- [Requirements](#requirements)
- [License](#license)

## Overview

This repository contains utility scripts designed to streamline various system administration tasks including:
- **Automation**: Automated backups, log archiving, git synchronization, and scheduled job management
- **Maintenance**: System health monitoring, log rotation, disk cleanup, and service management
- **Security**: Firewall auditing, IP blocking, SSL certificate validation, and network monitoring
- **Penetration Testing**: Security testing tools and utilities

## Directory Structure

```
bash_scripts/
├── automation_scripts/     # Automated system tasks
├── maintenance_scripts/    # System maintenance and monitoring
├── pentesting_scripts/     # Penetration testing utilities
└── security_scripts/       # Security hardening and monitoring
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/AliasUnknown710/bash_scripts.git
cd bash_scripts
```

2. Make scripts executable:
```bash
chmod +x automation_scripts/*.sh
chmod +x maintenance_scripts/*.sh
chmod +x security_scripts/*.sh
chmod +x pentesting_scripts/*.sh
```

## Scripts

### Automation Scripts

| Script | Purpose |
|--------|---------|
| `Archive_Logs.sh` | Automatically archive log files for storage optimization |
| `Auto_Backup.sh` | Create scheduled automated backups |
| `Cron_Audit.sh` | Audit and verify cron job configurations |
| `Cron_Job_Linter.sh` | Validate and lint cron job syntax |
| `Extract_Archives.sh` | Extract compressed archives with error handling |
| `Git_Auto_Pull.sh` | Automatically pull updates from git repositories |
| `Installer.sh` | Automated installation script for dependencies |
| `Syslog_Forwarder.sh` | Forward system logs to remote syslog servers |

### Maintenance Scripts

| Script | Purpose |
|--------|---------|
| `Config_Validator.sh` | Validate system configuration files |
| `Directory_Integrity.sh` | Check and verify directory structure integrity |
| `Disk_Cleanup.sh` | Clean up disk space and remove unnecessary files |
| `Kill_Idle_Process.sh` | Terminate idle/inactive processes |
| `Log_Parser.sh` | Parse and analyze log files |
| `Log_Rotation.sh` | Rotate and archive old log files |
| `Memory_Check.sh` | Monitor system memory usage |
| `multi_domain_check.sh` | Check health status of multiple domains |
| `Restart_Service.sh` | Safely restart system services |
| `Service_Health_Monitor.sh` | Monitor service health and availability |

### Security Scripts

| Script | Purpose |
|--------|---------|
| `Block_Bad_IPs.sh` | Block malicious IP addresses |
| `Firewall_Audit.sh` | Audit firewall rules and configurations |
| `Firewall_Hardening.sh` | Harden firewall security settings |
| `Ping_Monitor.sh` | Monitor network connectivity via ping |
| `SSL_Cert_Checker.sh` | Validate SSL certificate expiration and validity |

### Penetration Testing Scripts

| Script | Purpose |
|--------|---------|
| `hydra_brute.sh` | Automated password cracking using Hydra |

## Usage

Each script can be run directly from the command line:

```bash
./automation_scripts/Auto_Backup.sh
./maintenance_scripts/Disk_Cleanup.sh
./security_scripts/SSL_Cert_Checker.sh
```

For specific usage instructions, refer to the comments within each script or run with the `--help` or `-h` flag if available.

## Requirements

- Bash 4.0 or higher
- Linux/Unix-based operating system
- Standard Unix utilities (grep, sed, awk, etc.)
- Elevated privileges (sudo) for some scripts

Individual scripts may require additional tools:
- `Git_Auto_Pull.sh`: git
- `Syslog_Forwarder.sh`: rsyslog
- `hydra_brute.sh`: hydra
- `SSL_Cert_Checker.sh`: openssl

## License

This project is provided as-is for educational and administrative purposes.

## Contributing

Contributions are welcome. Please ensure scripts follow best practices and include appropriate error handling.

## Disclaimer

⚠️ **Security Notice**: Penetration testing scripts should only be used on systems you own or have explicit permission to test. Unauthorized access to computer systems is illegal.

