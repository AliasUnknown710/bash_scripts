# Log_Parser.sh

Parse and analyze log files.

## Description

This script analyzes log files to extract useful information, identify patterns, and generate summaries and reports.

## Usage

```bash
./Log_Parser.sh [OPTIONS] LOGFILE
```

## Options

- `-f, --filter`: Filter pattern for specific log entries
- `-c, --count`: Count occurrences of pattern
- `-t, --time-range`: Specify time range for analysis
- `-r, --report`: Generate analysis report
- `-h, --help`: Display help message

## Example

```bash
./Log_Parser.sh --filter "ERROR" --report /var/log/app.log
```

## Features

- Pattern matching and extraction
- Error aggregation and statistics
- Time-based log filtering
- Report generation

## Requirements

- Bash 4.0+
- Standard text processing utilities (grep, awk, sed, etc.)
- Read access to log files

## Output

Parsed log analysis and optional report file.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Log_Rotation.sh](Log_Rotation.sh)
- [Syslog_Forwarder.sh](../automation_scripts/Syslog_Forwarder.sh)
