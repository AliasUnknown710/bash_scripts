# Restart_Service.sh

Safely restart system services.

## Description

This script safely restarts system services with health checks, automatic rollback on failure, and logging of the restart process.

## Usage

```bash
./Restart_Service.sh [OPTIONS] SERVICE_NAME
```

## Options

- `-c, --check`: Health check command
- `-t, --timeout`: Timeout in seconds for restart
- `-r, --rollback`: Enable automatic rollback on failure
- `-s, --status`: Check service status before restarting
- `-h, --help`: Display help message

## Example

```bash
./Restart_Service.sh --check "systemctl is-active" --timeout 30 nginx
```

## Requirements

- Bash 4.0+
- systemctl or service command
- Elevated privileges (sudo/root)

## Safety Features

- Pre-restart health checks
- Timeout protection
- Rollback capability
- Detailed logging

## Output

Restart status, health check results, and operation summary.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Service_Health_Monitor.sh](Service_Health_Monitor.sh)
- [Config_Validator.sh](Config_Validator.sh)
