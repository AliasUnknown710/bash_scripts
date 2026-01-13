# Auto_Backup.sh

Create scheduled automated backups.

## Description

This script automates the backup process by creating full or incremental backups of specified directories on a regular schedule.

## Usage

```bash
./Auto_Backup.sh [OPTIONS]
```

## Options

- `-s, --source`: Source directory to backup
- `-d, --destination`: Backup destination directory
- `-t, --type`: Backup type (full, incremental)
- `-r, --retention`: Retention period in days
- `-h, --help`: Display help message

## Example

```bash
./Auto_Backup.sh --source /home/user --destination /backups --type full --retention 30
```

## Requirements

- Bash 4.0+
- tar, rsync, or similar backup utilities
- Sufficient disk space at destination
- Read permissions on source directory

## Schedule

Can be integrated with cron for automatic scheduling:

```bash
# Run daily at 2 AM
0 2 * * * /path/to/Auto_Backup.sh
```

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Cron_Audit.sh](Cron_Audit.sh)
- [Extract_Archives.sh](Extract_Archives.sh)
