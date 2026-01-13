# Directory_Integrity.sh

Check and verify directory structure integrity.

## Description

This script scans directory structures to verify permissions, ownership, and file integrity using checksums.

## Usage

```bash
./Directory_Integrity.sh [OPTIONS] DIRECTORY
```

## Options

- `-c, --checksum`: Verify file checksums
- `-p, --permissions`: Check file permissions
- `-o, --ownership`: Check ownership
- `-r, --report`: Generate integrity report
- `-h, --help`: Display help message

## Example

```bash
./Directory_Integrity.sh --checksum --permissions --report /var/www
```

## Requirements

- Bash 4.0+
- Standard utilities (find, stat, md5sum, etc.)
- Read access to target directory

## Output

Reports directory structure status, permission issues, and integrity violations.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Config_Validator.sh](Config_Validator.sh)
- [Disk_Cleanup.sh](Disk_Cleanup.sh)
