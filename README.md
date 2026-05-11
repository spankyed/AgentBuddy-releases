# AgentBuddy

A local-first desktop app for building and running AI agent workflows using an actor-based architecture.

## Download

Download the latest release from the [Releases page](https://github.com/spankyed/AgentBuddy-releases/releases/latest).

| Platform | Architecture | Format |
|----------|-------------|--------|
| macOS | Apple Silicon (arm64) | `.dmg` |

<!-- Windows and Linux builds coming soon -->

## System Requirements

- macOS 12+ (Apple Silicon)

## Getting Started

1. Download and install the `.dmg` from the [latest release](https://github.com/spankyed/AgentBuddy-releases/releases/latest)
2. Open AgentBuddy
3. Go to **Settings** and add your LLM API key (Anthropic, OpenAI, or Google)
4. Start building workflows

## Features

- **Actor-based architecture** — XState state machines drive frontend and backend through a typed event bus
- **LLM integration** — Connect to Anthropic, OpenAI, and Google models via the Vercel AI SDK
- **Visual node editor** — Design agent flows with drag-and-drop canvas
- **Embedded terminal** — Run commands directly inside the app
- **Thread-based conversations** — Persistent, resumable coding sessions
- **Interactive tool approval** — Approve or deny edit, write, and bash actions
- **Plugin system** — Extend the app with custom canvas views, panels, and state machines

## FAQ

**Do I need an API key?**
Not necessarily. AgentBuddy integrates with the Claude Code CLI, so you can use your existing Anthropic subscription. OpenAI Codex integration is coming soon. You can also connect directly with your own API key (Anthropic, OpenAI, or Google) in **Settings**.

**Is my data stored locally?**
Yes. All data stays on your machine — conversations, workflows, and settings are persisted locally via an embedded database.

**Can I customize the built-in actions and prompts?**
Yes. The [Default Setup](https://github.com/spankyed/default-setup) repo contains the source for all built-in actions, prompts, flows, and library docs. You can fork it, modify it, compile it, and import your custom setup pack via **Settings > Import Setup Pack**.

**Why isn't the source code available?**
AgentBuddy is currently in early testing. The full source code is planned to be released on June 19th, 2026.

**What models are supported?**
Any model available through Anthropic, OpenAI, or Google APIs via the Vercel AI SDK.

**Is Windows or Linux supported?**
Not yet — only macOS (Apple Silicon) builds are available currently. Windows and Linux support is planned.

## Links

- [Source & Documentation](https://github.com/spankyed/AgentBuddy)
- [Default Setup](https://github.com/spankyed/default-setup) — built-in actions, prompts, flows, and library docs