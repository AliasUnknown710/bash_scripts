# Archive_Logs.sh

Automatically archive log files for storage optimization.

## Description

This script identifies and compresses old log files, archiving them for long-term storage to free up disk space while maintaining historical records.

## Usage

```bash
./Archive_Logs.sh [OPTIONS]
```

## Options

- `-d, --directory`: Target directory containing log files
- `-a, --age`: Minimum age in days for files to archive
- `-c, --compress`: Compression format (gzip, bzip2, xz)
- `-h, --help`: Display help message

## Example

```bash
./Archive_Logs.sh --directory /var/log --age 30 --compress gzip
```

## Requirements

- Bash 4.0+
- Standard compression utilities (gzip, bzip2, or xz)
- Read/write permissions on target directory

## Output

Archives old logs to timestamped archive files with appropriate compression.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Log_Rotation.sh](Log_Rotation.sh)
- [Log_Parser.sh](Log_Parser.sh)
