# Maintenance Scripts

System maintenance and monitoring tools including health checks, log rotation, disk cleanup, and service management.

## Overview

This directory contains scripts for routine system maintenance tasks such as monitoring system health, managing logs, cleaning disk space, and ensuring services are running properly.

## Quick Start

```bash
chmod +x *.sh
./Memory_Check.sh
```

## Scripts

| Script | Purpose |
|--------|---------|
| [Config_Validator.sh](Config_Validator.sh) | Validate system configuration files |
| [Directory_Integrity.sh](Directory_Integrity.sh) | Check and verify directory structure integrity |
| [Disk_Cleanup.sh](Disk_Cleanup.sh) | Clean up disk space and remove unnecessary files |
| [Kill_Idle_Process.sh](Kill_Idle_Process.sh) | Terminate idle/inactive processes |
| [Log_Parser.sh](Log_Parser.sh) | Parse and analyze log files |
| [Log_Rotation.sh](Log_Rotation.sh) | Rotate and archive old log files |
| [Memory_Check.sh](Memory_Check.sh) | Monitor system memory usage |
| [multi_domain_check.sh](multi_domain_check.sh) | Check health status of multiple domains |
| [Restart_Service.sh](Restart_Service.sh) | Safely restart system services |
| [Service_Health_Monitor.sh](Service_Health_Monitor.sh) | Monitor service health and availability |

## Common Usage

Each script in this directory can be executed directly:

```bash
./Memory_Check.sh
```

For more detailed information about each script, refer to the individual README files in this directory.

## Requirements

- Bash 4.0+
- Standard GNU utilities (sed, awk, grep, etc.)
- System access privileges for monitoring and maintenance tasks
- Standard Linux/Unix utilities (ps, systemctl, etc.)

## License

MIT License - See [LICENSE](../LICENSE) for details
