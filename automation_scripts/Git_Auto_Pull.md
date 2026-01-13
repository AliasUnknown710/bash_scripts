# Git_Auto_Pull.sh

Automatically pull updates from git repositories.

## Description

This script automatically fetches and pulls updates from git repositories, keeping local copies synchronized with remote changes.

## Usage

```bash
./Git_Auto_Pull.sh [OPTIONS]
```

## Options

- `-r, --repo`: Repository path
- `-b, --branch`: Branch to pull from
- `-s, --stash`: Stash changes before pulling
- `-h, --help`: Display help message

## Example

```bash
./Git_Auto_Pull.sh --repo /home/user/myproject --branch main
```

## Requirements

- Bash 4.0+
- git installed and configured
- Read/write access to repository directory

## Schedule

Can be integrated with cron for automatic synchronization:

```bash
# Pull updates every hour
0 * * * * /path/to/Git_Auto_Pull.sh --repo /path/to/repo
```

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Auto_Backup.sh](Auto_Backup.sh)
- [Cron_Audit.sh](Cron_Audit.sh)
