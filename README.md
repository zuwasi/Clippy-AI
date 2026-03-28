# 📎 Clippy AI Assistant

A standalone desktop app that brings back the legendary Microsoft Office Clippy — now powered by modern AI!

![Clippy AI](https://img.shields.io/badge/Powered%20by-AI-blue) ![Platform](https://img.shields.io/badge/Platform-Windows-0078d4) ![Electron](https://img.shields.io/badge/Built%20with-Electron-47848f)

## Features

- **Classic Clippy** — animated paperclip assistant with authentic retro Windows UI
- **Modern AI backend** — connects to OpenAI, LM Studio, Ollama, or any OpenAI-compatible API
- **Full conversation memory** — maintains context across your chat session
- **Clippy persona** — AI responds in character as Clippy with his classic personality
- **Retro Windows theme** — teal background, gray window chrome, 90s nostalgia
- **Standalone desktop app** — runs without a browser

## Installation

### From Installer
1. Download the latest installer from [Releases](https://github.com/zuwasi/Clippy-AI/releases)
2. Run the installer
3. Launch "Clippy AI Assistant" from desktop or Start Menu

### From Source
```bash
git clone https://github.com/zuwasi/Clippy-AI.git
cd Clippy-AI
npm install
npm start
```

### Build Installer
```bash
npm run dist
```
The installer will be in the `dist/` folder.

## Configuration

On first launch, click the **⚙️ AI Settings** bar and configure:

| Setting  | Description |
|----------|-------------|
| Provider | OpenAI or Custom (LM Studio / Ollama) |
| API URL  | Endpoint URL for the AI service |
| API Key  | Your API key (stored locally only) |
| Model    | Model name (e.g., `gpt-4o-mini`) |

Settings are saved in your browser's localStorage and persist between sessions.

## Supported AI Backends

- **OpenAI** — `gpt-4o-mini`, `gpt-4o`, `gpt-4`, etc.
- **LM Studio** — local models at `http://localhost:1234/v1/chat/completions`
- **Ollama** — local models at `http://localhost:11434/v1/chat/completions`
- **Any OpenAI-compatible API**

## License

MIT
