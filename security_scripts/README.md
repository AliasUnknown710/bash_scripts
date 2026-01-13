# Security Scripts

Security hardening and monitoring tools including firewall management, IP blocking, SSL certificate validation, and network monitoring.

## Overview

This directory contains scripts focused on security hardening and continuous security monitoring to protect your system from threats.

## Quick Start

```bash
chmod +x *.sh
./SSL_Cert_Checker.sh
```

## Scripts

| Script | Purpose |
|--------|---------|
| [Block_Bad_IPs.sh](Block_Bad_IPs.sh) | Block malicious IP addresses |
| [Firewall_Audit.sh](Firewall_Audit.sh) | Audit firewall rules and configurations |
| [Firewall_Hardening.sh](Firewall_Hardening.sh) | Harden firewall security settings |
| [Ping_Monitor.sh](Ping_Monitor.sh) | Monitor network connectivity via ping |
| [SSL_Cert_Checker.sh](SSL_Cert_Checker.sh) | Validate SSL certificate expiration and validity |

## Common Usage

Each script in this directory can be executed directly:

```bash
./SSL_Cert_Checker.sh
```

For more detailed information about each script, refer to the individual README files in this directory.

## Requirements

- Bash 4.0+
- Standard GNU utilities (sed, awk, grep, etc.)
- Elevated privileges (sudo/root) for firewall and IP blocking operations
- openssl for SSL certificate validation
- iptables or firewall-cmd (depending on system)

## Security Notice

⚠️ Some scripts in this directory require elevated privileges. Use with caution and ensure proper authorization before executing.

## License

MIT License - See [LICENSE](../LICENSE) for details
