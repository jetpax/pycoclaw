# PycoClaw

**OpenClaw for Embedded** — AI agents on a $5 chip.

[![Website](https://img.shields.io/badge/pycoclaw.com-live-brightgreen)](https://pycoclaw.com)
[![Install](https://img.shields.io/badge/Install-Now-blue)](https://pycoclaw.com/install)

## What is PycoClaw?

PycoClaw is an open-source platform for running AI agents on ESP32 microcontrollers. It brings [OpenClaw](https://github.com/openclaw/openclaw)-compatible intelligence to embedded devices costing under $5.

Built on MicroPython, it supports:

- 🧠 **Multi-provider LLM routing** (OpenAI, Gemini, Ollama, etc.)
- 💬 **Multi-channel chat** (Telegram, Studio, WebRTC)
- 🔧 **Tool calling** with async execution
- 🧩 **Extensions** via [ScriptoHub](https://scriptohub.com)
- 📡 **Over-the-air updates** via [Scripto Studio](https://scriptostudio.com)
- 🔋 **Battery operation** with last-gasp flash saves

## Quick Start

1. **Get hardware** — any ESP32-S3 board with 16MB flash + PSRAM (~$5)
2. **Install firmware** — visit [pycoclaw.com/install](https://pycoclaw.com/install)
3. **Open Studio** — manage your device at [scriptostudio.com](https://scriptostudio.com)

## Architecture

```
┌──────────────────────────────────┐
│          Scripto Studio          │  Web IDE + Device Manager
├──────────────────────────────────┤
│          ScriptoHub              │  Extension Marketplace
├──────────────────────────────────┤
│     PFC (Prefrontal Cortex)      │  AI Agent Orchestrator
├──────────────────────────────────┤
│          pyDirect                │  MicroPython + Native C modules
├──────────────────────────────────┤
│        ESP32-S3 Hardware         │  WiFi · BLE · USB · PSRAM
└──────────────────────────────────┘
```

## Platforms

| Platform | Chip | Status |
|----------|------|--------|
| ESP32-S3 | Xtensa LX7 | ✅ Production |
| RP2350 | ARM Cortex-M33 | 🚧 Coming Soon |

## Related Projects

- [Scripto Studio](https://github.com/jetpax/scripto-studio) — Web-based IDE
- [ScriptoHub](https://github.com/jetpax/scriptohub) — Extension marketplace
- [WebREPL](https://github.com/jetpax/webrepl) — Protocol specifications
- [USRobotIQ](https://usrobotiq.com) — Consumer products

## License

MIT — Copyright © 2026 Jonathan Peace

## Contact

**Jonathan Peace**  
Email: jep@alphabetiq.com
