# Cron_Audit.sh

Audit and verify cron job configurations.

## Description

This script analyzes cron jobs across the system, verifying their configurations and identifying potential issues or inconsistencies.

## Usage

```bash
./Cron_Audit.sh [OPTIONS]
```

## Options

- `-u, --user`: Audit cron jobs for specific user
- `-v, --verbose`: Verbose output with detailed information
- `-r, --report`: Generate audit report file
- `-h, --help`: Display help message

## Example

```bash
./Cron_Audit.sh --user root --verbose --report /tmp/cron_audit.txt
```

## Requirements

- Bash 4.0+
- Access to crontab files
- Standard text processing utilities (grep, awk, etc.)

## Output

Displays or reports on cron job status, schedule validity, and potential issues.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Cron_Job_Linter.sh](Cron_Job_Linter.sh)
- [Auto_Backup.sh](Auto_Backup.sh)
