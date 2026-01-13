# Syslog_Forwarder.sh

Forward system logs to remote syslog servers.

## Description

This script configures and manages forwarding of system logs to remote syslog servers for centralized log management and archiving.

## Usage

```bash
./Syslog_Forwarder.sh [OPTIONS]
```

## Options

- `-s, --server`: Remote syslog server address
- `-p, --port`: Remote syslog port (default: 514)
- `-f, --facility`: Syslog facility
- `-t, --protocol`: Protocol (udp, tcp, ssl)
- `-h, --help`: Display help message

## Example

```bash
./Syslog_Forwarder.sh --server syslog.example.com --port 514 --protocol tcp
```

## Requirements

- Bash 4.0+
- rsyslog or similar logging daemon
- Network connectivity to syslog server
- Elevated privileges for syslog configuration

## Output

Configures syslog forwarding and reports configuration status.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Log_Parser.sh](../maintenance_scripts/Log_Parser.sh)
- [Log_Rotation.sh](../maintenance_scripts/Log_Rotation.sh)
