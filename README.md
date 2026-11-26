# Ferrite

Where what your coding agent builds goes to live.

Build, deploy and run full-stack web apps from the conversation. You describe the application to a coding agent such as Claude Code, Codex or Cursor; the agent writes it, checks it and deploys it to Ferrite Cloud, and you get back a URL that serves it, with its storage, queues and routing provided by the platform.

This repository is the front door for Ferrite on GitHub. It holds no code. It is where problems with the hosted platform are reported, and it links to the repositories that do hold code.

## Start

Install the `ferrite` CLI, which also connects your coding agent to your Ferrite account:

```bash
curl -fsSL https://downloads.ferrite.cloud/install.sh | sh
```

An agent that cannot install software can use the hosted MCP server instead. Add this address to the agent as a remote MCP server and sign in when it asks:

```text
https://mcp.ferrite.cloud/mcp
```

The [documentation](https://docs.ferrite.cloud) covers both routes for each agent.

## Repositories

| Repository | Contents |
| --- | --- |
| [ferrite-plugin](https://github.com/iGentAI/ferrite-plugin) | The Ferrite plugin for coding agents: the skill, the MCP configuration and the manifest each agent reads |
| [ferrite-cli](https://github.com/iGentAI/ferrite-cli) | The installer and the release archives of the `ferrite` CLI, with their checksums |
| [ferrite-packages](https://github.com/iGentAI/ferrite-packages) | Source packages that `ferrite add` installs into an application, and the package index |
| [ferrite-examples](https://github.com/iGentAI/ferrite-examples) | Complete sample applications that build and test on your own machine |
| [ferrite-sdk](https://github.com/iGentAI/ferrite-sdk) | The Rust crates a Ferrite application is written against, with the local test harness and checker |
| [ferrite-docs](https://github.com/iGentAI/ferrite-docs) | The source of the documentation at docs.ferrite.cloud |
| [ferrite-agent-ready](https://github.com/iGentAI/ferrite-agent-ready) | Scanners that measure how well a website serves AI agents |
| [ferrite-agent-matrix](https://github.com/iGentAI/ferrite-agent-matrix) | How each coding agent connects to an MCP server, client by client |
| [ferrite-showcase-buzz](https://github.com/iGentAI/ferrite-showcase-buzz) | Buzz on Ferrite: a team workspace for people and AI teammates, rebuilt as one Ferrite application |
| [ferrite-showcase-swatchbook](https://github.com/iGentAI/ferrite-showcase-swatchbook) | Swatchbook: a palette gallery whose design is data, made to be forked and restyled |

Each repository states its own licence in its `LICENSE` file. The hosted Ferrite platform is proprietary and not open source.

## Links

- Website: <https://ferrite.cloud>
- Documentation: <https://docs.ferrite.cloud>
- Dashboard: <https://dashboard.ferrite.cloud>
- Terms of service: <https://ferrite.cloud/terms>
- Privacy: <https://ferrite.cloud/privacy>

## Help and reporting

Report a problem with the hosted platform as an issue in this repository, or write to info@igent.ai; `SUPPORT.md` says what to include. Report a security problem privately to security@ferrite.cloud, as `SECURITY.md` describes. The change log is in `CHANGELOG.md`.
