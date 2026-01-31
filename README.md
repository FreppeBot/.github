# FreppeBot

**Self-hosted AI assistant with an easy plugin system**

FreppeBot is a powerful, self-hosted AI assistant that runs on Discord and Telegram. It combines modern AI models (Claude, GPT-5, etc.) with a flexible plugin architecture, giving you full control over your assistant's capabilities.

## Key Features

- **Multi-Platform**: Discord & Telegram support
- **Multiple AI Providers**: OpenRouter, OpenAI, Anthropic, Kimi
- **Plugin System**: Easy-to-write plugins for extending functionality
- **Built-in Tools**: File management, web search, reminders, GitHub integration, and more
- **Hot Reload**: Update plugins without restarting
- **Health Monitoring**: Built-in TUI dashboard
- **Security**: Rate limiting, input validation, admin controls

## Architecture

Built with Node.js using an event-driven, modular architecture:
- **Adapter Pattern**: Platform abstraction (Discord/Telegram)
- **Plugin Registry**: Dynamic command and tool registration
- **AI Manager**: Provider-agnostic AI interactions with tool calling
- **Message Router**: Intelligent routing with rate limiting and validation
- **SQLite Storage**: Persistent memory and reminders

## Quick Start

npm install
npm run setup
npm start## Documentation

Full documentation, plugin development guide, and API reference available in the main repository.

---

**Tech Stack**: Node.js, Discord.js, Telegraf, SQL.js, Multiple AI Providers
