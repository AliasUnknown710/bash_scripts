# Ping_Monitor.sh

Monitor network connectivity via ping.

## Description

This script monitors network connectivity to specified hosts using ICMP ping, providing alerts and statistics on network reliability.

## Usage

```bash
./Ping_Monitor.sh [OPTIONS]
```

## Options

- `-h, --host`: Host or IP to ping
- `-f, --file`: File with list of hosts to monitor
- `-i, --interval`: Ping interval in seconds
- `-c, --count`: Number of pings per check
- `-e, --email`: Email alerts on connectivity loss
- `-r, --report`: Generate connectivity report
- `--help`: Display help message

## Example

```bash
./Ping_Monitor.sh --host example.com --interval 30 --report /tmp/ping.log
```

## Features

- Continuous connectivity monitoring
- Multi-host support
- Response time tracking
- Packet loss statistics
- Alert notifications

## Requirements

- Bash 4.0+
- ping utility
- Network connectivity
- Mail utility for alerts (optional)

## Output

Connectivity status and statistics.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [multi_domain_check.sh](../maintenance_scripts/multi_domain_check.sh)
- [Service_Health_Monitor.sh](../maintenance_scripts/Service_Health_Monitor.sh)
