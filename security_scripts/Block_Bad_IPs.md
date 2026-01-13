# Block_Bad_IPs.sh

Block malicious IP addresses.

## Description

This script manages firewall rules to block identified malicious or unwanted IP addresses, supporting both static and dynamic blocking.

## Usage

```bash
./Block_Bad_IPs.sh [OPTIONS]
```

## Options

- `-i, --ip`: IP address to block
- `-f, --file`: File containing list of IPs to block
- `-u, --unblock`: Unblock IP address
- `-l, --list`: List currently blocked IPs
- `-p, --permanent`: Make blocking permanent
- `-h, --help`: Display help message

## Example

```bash
./Block_Bad_IPs.sh --file malicious_ips.txt --permanent
```

## Data Sources

- Firewall logs analysis
- Intrusion detection alerts
- External threat intelligence
- Manual blocklists

## Requirements

- Bash 4.0+
- iptables or firewall-cmd
- Elevated privileges (sudo/root)
- Network configuration knowledge

## Output

Confirms IP blocking and lists current firewall rules.

## ⚠️ Warning

Verify IPs before blocking to avoid blocking legitimate traffic.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Firewall_Audit.sh](Firewall_Audit.sh)
- [Firewall_Hardening.sh](Firewall_Hardening.sh)
