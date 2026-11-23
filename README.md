# BugX Kimi Plugin

[![Release](https://img.shields.io/github/v/release/Bencibr/bugx-kimi-plugin?color=blue)](https://github/Bencibr/bugx-kimi-plugin/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

BugX plugin for **Kimi Code CLI** and **Kimi Work**.

Provides an autonomous code review, vulnerability hunting, and automated verification agent directly integrated with Kimi Code.

## Features

- **Autonomous Code Audit**: Explores codebase, finds subtle logic flaws and security vulnerabilities.
- **Reproducible PoC**: Automatically generates verifiable test scripts to prove bugs before suggesting fixes.
- **MCP Integration**: Direct connection with `bugx-supervisor` and `bugx-docs` MCP servers.

## Installation

### Prerequisites

Install the BugX CLI:

```bash
npm install -g @bugx/cli
# Or using pip:
pip install bugx
```

### Install in Kimi Code CLI

Install directly from GitHub:

```bash
kimi plugin install https://github.com/Bencibr/bugx-kimi-plugin/archive/refs/heads/main.zip
```

Or via Kimi Code chat:

```text
/plugins install https://github.com/Bencibr/bugx-kimi-plugin
```

## Usage

In your project directory, launch Kimi Code:

```bash
kimi
```

Then invoke BugX:

```text
@bugx Audit authentication and API authorization logic in this project.
```

## License

MIT License. See [LICENSE](LICENSE) for details.
