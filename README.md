# google-ai-workaround

![Audit](https://img.shields.io/badge/audit%3A%20PASS-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![OpenClaw](https://img.shields.io/badge/OpenClaw-skill-orange)

> Automates Google AI Pro/Ultra access management through proxy and session strategies for OpenClaw agents.

## Features

- Detects Google AI service restrictions by analyzing HTTP response patterns
- Manages proxy configurations with round-robin, least-used, and random rotation strategies
- Provides a CLI interface for manual testing and configuration verification
- Integrates with OpenClaw agent workflows for seamless automation
- Monitors access patterns and identifies rate limiting
- Handles authentication token refresh and session persistence
- Generates detailed logs and error reports for troubleshooting

## Configuration

- `--config <path>` - Path to config file (default: `assets/config-template.json`)
- `--silent` - Suppress log output
- `--log-file <path>` - Write logs to a file

## GitHub

Source code: [github.com/NeoSkillFactory/google-ai-workaround](https://github.com/NeoSkillFactory/google-ai-workaround)

## License

MIT © NeoSkillFactory