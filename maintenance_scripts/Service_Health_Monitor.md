# Service_Health_Monitor.sh

Monitor service health and availability.

## Description

This script continuously monitors the health and availability of system services, providing alerts when services fail or become unresponsive.

## Usage

```bash
./Service_Health_Monitor.sh [OPTIONS]
```

## Options

- `-s, --service`: Service name to monitor
- `-i, --interval`: Check interval in seconds
- `-t, --timeout`: Response timeout in seconds
- `-e, --email`: Email alerts on failure
- `-a, --auto-restart`: Automatically restart failed services
- `-h, --help`: Display help message

## Example

```bash
./Service_Health_Monitor.sh --service nginx --interval 60 --auto-restart
```

## Features

- Continuous health monitoring
- Response time tracking
- Failure alerts
- Auto-restart capability
- Historical tracking

## Requirements

- Bash 4.0+
- systemctl or service command
- Standard monitoring utilities
- Mail utility for alerts (optional)

## Output

Real-time health status and alerts.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Restart_Service.sh](Restart_Service.sh)
- [Kill_Idle_Process.sh](Kill_Idle_Process.sh)
