# Disk_Cleanup.sh

Clean up disk space and remove unnecessary files.

## Description

This script identifies and safely removes unnecessary files, temporary data, and cache to free up disk space.

## Usage

```bash
./Disk_Cleanup.sh [OPTIONS]
```

## Options

- `-d, --directory`: Target directory for cleanup
- `-t, --type`: File type to clean (temp, cache, logs, etc.)
- `-a, --age`: Minimum age in days for file deletion
- `-d, --dry-run`: Show what would be deleted without removing
- `-h, --help`: Display help message

## Example

```bash
./Disk_Cleanup.sh --directory /var --type temp --age 7 --dry-run
```

## Safe Cleanup Targets

- Temporary files
- Old cache data
- System temporary directories
- Log files (with retention policy)

## Requirements

- Bash 4.0+
- Standard utilities (find, du, rm, etc.)
- Write permissions on target directories

## Output

Reports freed disk space and cleanup summary.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Log_Rotation.sh](Log_Rotation.sh)
- [Memory_Check.sh](Memory_Check.sh)
