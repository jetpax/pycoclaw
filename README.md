# PycoClaw

**OpenClaw for Embedded** — AI agents on a $5 chip.

[![Website](https://img.shields.io/badge/pycoclaw.com-live-brightgreen)](https://pycoclaw.com)
[![Install](https://img.shields.io/badge/Install-Now-blue)](https://pycoclaw.com/install)


![App Screenshot](images/pycoclaw-screenshot.png)

## What is PycoClaw?

PycoClaw is an open-source platform for running AI agents on microcontrollers. 

It brings [OpenClaw](https://github.com/openclaw/openclaw) workspace-compatible intelligence to embedded devices costing under $5.

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
│     PFC (Prefrontal Cortex)      │  AI Agent Orchestrator
├──────────────────────────────────┤
│          ScriptoHub              │  Extension Marketplace
├──────────────────────────────────┤
│          Scripto Studio          │  PWA IDE + Device Manager
├──────────────────────────────────┤
│          MicroPython             │  + Native C modules
├──────────────────────────────────┤
│        ESP32-S3 Hardware         │  WiFi · BLE · USB · PSRAM
└──────────────────────────────────┘
```

## Platforms

| Platform | Chip | Status |
|----------|------|--------|
| ESP32-S3 | Xtensa LX7 | ✅ Production |
| ESP32-P4 | RISC-V | ✅ Production |
| RP2350 | ARM Cortex-M33 | 🚧 Coming Soon |


## Star History

<a href="https://www.star-history.com/?repos=jetpax%2Fpycoclaw&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/image?repos=jetpax/pycoclaw&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/image?repos=jetpax/pycoclaw&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/image?repos=jetpax/pycoclaw&type=date&legend=top-left" />
 </picture>
</a>

## Related Projects

- [ScriptoHub](https://scriptohub.ai) — Skills & Extension marketplace
- [Scripto Studio](https://scriptostudio.com) — PWA IDE + Device Manager
- [WebREPL](https://github.com/jetpax/webrepl) — Protocol specifications
- [USRobotIQ](https://usrobotiq.com) —  Robot, code thyself!

## License

MIT — Copyright © 2026 Jonathan Peace

## Contact

**Jonathan Peace**  
Email: jep@alphabetiq.com
