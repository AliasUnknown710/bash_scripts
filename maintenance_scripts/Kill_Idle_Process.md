# Kill_Idle_Process.sh

Terminate idle/inactive processes.

## Description

This script identifies processes that have been idle for a specified duration and safely terminates them to free system resources.

## Usage

```bash
./Kill_Idle_Process.sh [OPTIONS]
```

## Options

- `-i, --idle-time`: Idle time threshold in minutes
- `-u, --user`: Target specific user's processes
- `-p, --process`: Specific process name or pattern
- `-f, --force`: Force kill (SIGKILL) instead of graceful shutdown
- `-h, --help`: Display help message

## Example

```bash
./Kill_Idle_Process.sh --idle-time 30 --user www-data
```

## Requirements

- Bash 4.0+
- Standard utilities (ps, kill, etc.)
- Appropriate privileges to kill processes

## Output

Reports killed processes and resources freed.

## ⚠️ Warning

Use with caution. Verify processes before terminating.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Memory_Check.sh](Memory_Check.sh)
- [Service_Health_Monitor.sh](Service_Health_Monitor.sh)
