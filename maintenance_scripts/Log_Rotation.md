# Log_Rotation.sh

Rotate and archive old log files.

## Description

This script manages log file rotation, compressing and archiving old logs while maintaining a rolling retention period.

## Usage

```bash
./Log_Rotation.sh [OPTIONS]
```

## Options

- `-l, --logfile`: Log file to rotate
- `-r, --retention`: Retention period in days
- `-c, --compress`: Compress rotated logs
- `-s, --size`: Rotate when file size exceeds limit
- `-h, --help`: Display help message

## Example

```bash
./Log_Rotation.sh --logfile /var/log/app.log --retention 30 --compress
```

## Requirements

- Bash 4.0+
- Compression utilities (gzip, bzip2, etc.)
- Write permissions on log directory

## Cron Integration

```bash
# Rotate logs daily at midnight
0 0 * * * /path/to/Log_Rotation.sh --logfile /var/log/app.log
```

## Output

Rotates logs and maintains archive according to retention policy.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Log_Parser.sh](Log_Parser.sh)
- [Archive_Logs.sh](../automation_scripts/Archive_Logs.sh)
