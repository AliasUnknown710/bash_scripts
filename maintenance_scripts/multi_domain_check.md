# multi_domain_check.sh

Check health status of multiple domains.

## Description

This script monitors the health and availability of multiple domains, checking response times, DNS resolution, and SSL certificates.

## Usage

```bash
./multi_domain_check.sh [OPTIONS]
```

## Options

- `-f, --file`: Domain list file (one domain per line)
- `-d, --domains`: Comma-separated list of domains
- `-c, --check`: Check type (http, dns, ssl, all)
- `-r, --report`: Generate status report
- `-e, --email`: Email alerts on failure
- `-h, --help`: Display help message

## Example

```bash
./multi_domain_check.sh --file domains.txt --check all --report /tmp/report.html
```

## Checks Performed

- HTTP/HTTPS connectivity
- DNS resolution
- SSL certificate validity
- Response time measurement

## Requirements

- Bash 4.0+
- curl, dig, openssl
- Standard utilities (grep, awk, etc.)
- Network connectivity

## Output

Health status report with statistics and recommendations.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Ping_Monitor.sh](../security_scripts/Ping_Monitor.sh)
- [SSL_Cert_Checker.sh](../security_scripts/SSL_Cert_Checker.sh)
