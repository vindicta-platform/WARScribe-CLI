# WARScribe-CLI

Command-line interface for WARScribe notation and tools.

## Overview

WARScribe-CLI provides a unified command-line interface for working with WARScribe notation, including validation, conversion, and analysis of army lists and game data.

## Features

- **List Validation**: Verify army lists against ruleset
- **Format Conversion**: Convert between WARScribe formats
- **Quick Stats**: Command-line analysis and point calculations
- **Batch Processing**: Process multiple files

## Installation

Install from source using uv:

```bash
uv pip install git+https://github.com/vindicta-platform/WARScribe-CLI.git
```

Or clone and install locally:

```bash
git clone https://github.com/vindicta-platform/WARScribe-CLI.git
cd WARScribe-CLI
uv pip install -e .
```

## Quick Start

```bash
# Validate an army list
warscribe validate mylist.warscribe

# Convert to JSON
warscribe convert mylist.warscribe --format json

# Quick point summary
warscribe stats mylist.warscribe
```

## Commands

| Command | Description |
|---------|-------------|
| `validate` | Check list against rules |
| `convert` | Export to different formats |
| `stats` | Display army statistics |
| `diff` | Compare two lists |

## Related Repositories

| Repository | Relationship |
|------------|-------------|
| [WARScribe-Parser](https://github.com/vindicta-platform/WARScribe-Parser) | Core parsing library |
| [platform-core](https://github.com/vindicta-platform/platform-core) | Platform integration |

## Platform Documentation

> **📌 Important:** All cross-cutting decisions, feature proposals, and platform-wide architecture documentation live in [**Platform-Docs**](https://github.com/vindicta-platform/Platform-Docs).
>
> Any decision affecting multiple repos **must** be recorded there before implementation.

- 📋 [Feature Proposals](https://github.com/vindicta-platform/Platform-Docs/tree/main/docs/proposals)
- 🏗️ [Architecture Decisions](https://github.com/vindicta-platform/Platform-Docs/tree/main/docs)
- 📖 [Contributing Guide](https://github.com/vindicta-platform/Platform-Docs/blob/main/CONTRIBUTING.md)

## License

MIT License - See [LICENSE](./LICENSE) for details.
