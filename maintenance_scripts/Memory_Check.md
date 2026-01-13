# Memory_Check.sh

Monitor system memory usage.

## Description

This script monitors system memory usage, alerting when thresholds are exceeded and providing detailed memory statistics.

## Usage

```bash
./Memory_Check.sh [OPTIONS]
```

## Options

- `-t, --threshold`: Alert threshold percentage (default: 80%)
- `-v, --verbose`: Verbose output with detailed breakdown
- `-e, --email`: Email address for alerts
- `-r, --report`: Generate memory usage report
- `-h, --help`: Display help message

## Example

```bash
./Memory_Check.sh --threshold 75 --verbose --report /tmp/memory.txt
```

## Requirements

- Bash 4.0+
- Standard utilities (free, ps, etc.)
- Mail utility for email alerts (optional)

## Output

Displays or logs memory usage statistics and alerts when thresholds are exceeded.

## Metrics

- Total memory
- Used/Free memory
- Buffer/Cache memory
- Per-process memory breakdown (verbose mode)

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Disk_Cleanup.sh](Disk_Cleanup.sh)
- [Kill_Idle_Process.sh](Kill_Idle_Process.sh)
