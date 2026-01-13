# Firewall_Audit.sh

Audit firewall rules and configurations.

## Description

This script audits firewall rules and configurations, identifying open ports, suspicious rules, and potential security gaps.

## Usage

```bash
./Firewall_Audit.sh [OPTIONS]
```

## Options

- `-v, --verbose`: Verbose output with detailed rule analysis
- `-r, --report`: Generate audit report file
- `-p, --ports`: Check specific ports
- `-c, --compliance`: Check against security standards
- `-h, --help`: Display help message

## Example

```bash
./Firewall_Audit.sh --verbose --report /tmp/firewall_audit.txt --compliance
```

## Checks Performed

- Open ports verification
- Rule consistency
- Redundant rules identification
- Policy compliance verification
- Logging configuration review

## Requirements

- Bash 4.0+
- iptables, firewall-cmd, or similar
- Elevated privileges (sudo/root)

## Output

Detailed firewall audit report with recommendations.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Firewall_Hardening.sh](Firewall_Hardening.sh)
- [Block_Bad_IPs.sh](Block_Bad_IPs.sh)
