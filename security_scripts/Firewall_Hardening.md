# Firewall_Hardening.sh

Harden firewall security settings.

## Description

This script applies security hardening measures to the firewall, implementing best practices and closing common security gaps.

## Usage

```bash
./Firewall_Hardening.sh [OPTIONS]
```

## Options

- `-d, --default-policy`: Set default drop/reject policy
- `-l, --log`: Enable firewall logging
- `-s, --syn-protection`: Enable SYN flood protection
- `-a, --apply-all`: Apply all hardening measures
- `-h, --help`: Display help message

## Example

```bash
./Firewall_Hardening.sh --apply-all --log
```

## Hardening Measures

- Default drop policies
- Rate limiting
- SYN flood protection
- Port scanning detection
- Logging configuration
- Firewall state tracking

## Requirements

- Bash 4.0+
- iptables, firewall-cmd, or similar
- Elevated privileges (sudo/root)
- System restart may be required

## Output

Confirms hardening measures applied with configuration summary.

## ⚠️ Warning

May impact network connectivity. Test in controlled environment first.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Firewall_Audit.sh](Firewall_Audit.sh)
- [Block_Bad_IPs.sh](Block_Bad_IPs.sh)
