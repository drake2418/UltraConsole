# UltraConsole

A cross-platform AI-powered desktop console built with Electron. UltraConsole brings together a suite of specialized tools — all accessible from a unified dashboard with a built-in AI chat powered by Google Gemini, Claude, and Grok.

## Download

Grab the latest installer from the [Releases](../../releases) page.

- **Windows** — `UltraConsoleSetup-1.0.14.exe`
- **Mac-OS** — `UltraConsoleSetup-1.0.14.dmg` (Releasing Soon)

## Features

- **AI Chat Dashboard** — chat with Gemini, Claude, Grok, or local Gemma 4 models from one interface
- **DeepDive** — deep research and system diagnostics with AI
- **Atlas** — network scanning and analysis
- **Wikii** — personal knowledge base manager
- **InstaGen** — AI image generation
- **Ultra Orb** — live voice AI assistant
- **Link** — SSH manager and terminal
- **Local AI** — run Gemma 4 fully on-device via Ollama (no API key needed)
- **Auto-Updates** — built-in update system


## AI Model Support

| Provider | Models |
|---|---|
| Google Gemini | Gemini 3.5 Flash, Gemini 3.1 Flash Lite, Gemini 3.1 Pro, Gemini 3 Flash |
| Anthropic | Claude Opus 4.7, Claude Opus 4.6, Claude Sonnet 4.6, Claude Haiku 4.5 |
| xAI | Grok 4.1 Fast Reasoning |
| Local (Ollama) | Gemma 4 2B, 4B, 26B |

## Project Structure

```
src/          Electron main process
public/       Dashboard UI (HTML/CSS/JS)
apps/         Built-in app suite (Brain, Atlas, Wikii, etc.)
server/       Local Express server & API proxy
MCP/          Model Context Protocol integrations
assets/       Icons and static assets
```

## License

MIT — see [LICENSE](LICENSE)
