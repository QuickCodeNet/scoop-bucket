# QuickCode CLI Scoop Bucket

Scoop bucket for [QuickCode CLI](https://github.com/QuickCodeNet/quickcode.cli) - A .NET 10 console application that mirrors the QuickCode web UI: create projects, manage modules, trigger generation and stream SignalR updates directly from the terminal.

## Installation

### Add this bucket

```powershell
scoop bucket add quickcode-cli https://github.com/QuickCodeNet/quickcode-cli-bucket
```

### Install QuickCode CLI

```powershell
scoop install quickcode-cli
```

## Update

To update QuickCode CLI to the latest version:

```powershell
scoop update quickcode-cli
```

Or update all packages from this bucket:

```powershell
scoop update *
```

## Uninstall

To remove QuickCode CLI:

```powershell
scoop uninstall quickcode-cli
```

## Documentation

For detailed documentation, usage examples, and command reference, visit the main repository:

**https://github.com/QuickCodeNet/quickcode.cli**

## Quick Start

After installation, verify it works:

```powershell
quickcode --version
```

Get help:

```powershell
quickcode --help
```

## Prerequisites

- Internet access to `https://api.quickcode.net/`
- Each project's email + secret must be known or retrievable via `project forgot-secret`

## License

MIT License - See the [main repository](https://github.com/QuickCodeNet/quickcode.cli) for details.

