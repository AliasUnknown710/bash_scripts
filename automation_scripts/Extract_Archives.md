# Extract_Archives.sh

Extract compressed archives with error handling.

## Description

This script safely extracts compressed archive files with robust error handling, supporting multiple formats and providing detailed feedback.

## Usage

```bash
./Extract_Archives.sh [OPTIONS] ARCHIVE_FILE
```

## Options

- `-d, --destination`: Extraction destination directory
- `-v, --verbose`: Verbose output
- `-t, --test`: Test archive integrity before extraction
- `-h, --help`: Display help message

## Example

```bash
./Extract_Archives.sh --destination /tmp --test backup.tar.gz
```

## Supported Formats

- .tar, .tar.gz, .tar.bz2, .tar.xz
- .zip
- .7z

## Requirements

- Bash 4.0+
- Appropriate extraction utilities (tar, unzip, 7z, etc.)
- Write permissions on destination directory

## Output

Extracts archive and reports success or errors with detailed messages.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Archive_Logs.sh](Archive_Logs.sh)
- [Auto_Backup.sh](Auto_Backup.sh)
