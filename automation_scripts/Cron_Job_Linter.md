# Cron_Job_Linter.sh

Validate and lint cron job syntax.

## Description

This script validates the syntax of cron jobs, checking for common errors and ensuring jobs will execute as intended.

## Usage

```bash
./Cron_Job_Linter.sh [OPTIONS]
```

## Options

- `-f, --file`: Crontab file to lint
- `-u, --user`: Validate cron jobs for specific user
- `-s, --strict`: Enable strict validation mode
- `-h, --help`: Display help message

## Example

```bash
./Cron_Job_Linter.sh --file /etc/crontab --strict
```

## Requirements

- Bash 4.0+
- Standard text processing utilities
- Read access to crontab files

## Output

Reports syntax errors, warnings, and validation results.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Cron_Audit.sh](Cron_Audit.sh)
- [Auto_Backup.sh](Auto_Backup.sh)
