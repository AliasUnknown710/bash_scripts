# SSL_Cert_Checker.sh

Validate SSL certificate expiration and validity.

## Description

This script checks SSL certificate validity and expiration dates, providing advance warnings for certificates nearing expiration.

## Usage

```bash
./SSL_Cert_Checker.sh [OPTIONS]
```

## Options

- `-h, --host`: Host to check SSL certificate
- `-f, --file`: Certificate file path
- `-d, --days`: Days before expiration to alert
- `-e, --email`: Email alerts for expiring certificates
- `-r, --report`: Generate certificate report
- `--help`: Display help message

## Example

```bash
./SSL_Cert_Checker.sh --host example.com --days 30 --report /tmp/certs.txt
```

## Checks Performed

- Certificate validity period
- Expiration date verification
- Chain validity
- Signature verification
- Hostname matching

## Requirements

- Bash 4.0+
- openssl utility
- Network connectivity (for remote certificates)
- Mail utility for alerts (optional)

## Output

Certificate validity report with expiration warnings.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [multi_domain_check.sh](../maintenance_scripts/multi_domain_check.sh)
- [Ping_Monitor.sh](Ping_Monitor.sh)
