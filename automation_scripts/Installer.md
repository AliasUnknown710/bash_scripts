# Installer.sh

Automated installation script for dependencies.

## Description

This script automates the installation of project dependencies and required packages, handling different package managers and systems.

## Usage

```bash
./Installer.sh [OPTIONS]
```

## Options

- `-p, --packages`: Package list or file
- `-m, --manager`: Package manager (apt, yum, brew, etc.)
- `-f, --force`: Force reinstallation
- `-h, --help`: Display help message

## Example

```bash
./Installer.sh --packages "curl wget git" --manager apt
```

## Requirements

- Bash 4.0+
- Appropriate package manager for system
- Elevated privileges (sudo/root) for package installation

## Output

Installs specified packages and reports success/failure for each.

## License

MIT License - See [LICENSE](../../LICENSE) for details

## See Also

- [Config_Validator.sh](../maintenance_scripts/Config_Validator.sh)
