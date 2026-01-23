<div align="center">

# 🌌 Antigravity: Skills Chronicle

**The premium management layer for AI Skills, powered by the ChronicleCore system.**

[![VS Code](https://img.shields.io/badge/VS%20Code-Extension-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://marketplace.visualstudio.com/items?itemName=ChronicleCore.antigravity-skills-chronicle)
[![License: SEE LICENSE](https://img.shields.io/badge/License-SEE%20README-red.svg?style=for-the-badge)](LICENSE)
[![Brand](https://img.shields.io/badge/Brand-ChronicleCore-B91C1C?style=for-the-badge)](https://buymeacoffee.com/zaious)

---

*Manage your AI Skills, Workflows, and Rules with a premium visual dashboard.*

</div>

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🛠️ **Skills Dashboard** | View and manage all skills in your `.agent/skills/` directory |
| 📜 **Workflow Manager** | Organize and execute workflows from `.agent/workflows/` |
| 📋 **Rules Inspector** | View and edit agent rules |
| 💬 **Conversation Archive** | Browse and search past Claude conversations |
| 📍 **Dynamic Status Bar** | Real-time skill and workflow count in the status bar |

---

## 📊 Status Bar Integration

![Status Bar](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/introduce/status-bar.png)

The extension provides a **real-time status bar** showing your current asset counts:
- **Skills**: Total AI skill definitions
- **Workflows**: Registered automation procedures
- **Rules**: Active governance policies

---

## 🖥️ Terminal Dashboard

![Terminal](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/introduce/terminal-dashboard.png)

The **Terminal View** is your command center:

| Section | Description |
|---------|-------------|
| **Skills / Workflows / Rules** | Quick count overview at a glance |
| **LSP Status Monitor** | Connection status of your Language Server Protocol |
| **Skill Hub** | One-click access to download official skill templates |

---

## 📁 Skill Detail: File Browser

![Skill Files](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/introduce/skill-detail-files.png)

Explore the internal structure of any skill:
- **File Tree**: Navigate folders and view source files directly
- **Skill Metadata**: Read the `SKILL.md` frontmatter with `x-vibe-stats` and gamified attributes
- **Reveal in Explorer**: Open the skill folder in your OS file manager

---

## ⚙️ Skill Detail: Configuration View

![Skill Config](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/introduce/skill-detail-config.png)

The **Configuration Tab** displays the parsed Chronicle Node Schema:
- **Vibe Stats**: Endurance, Accuracy, Creativity, Aggression
- **Identity Block**: Nickname and version standard
- **Visual Tokens**: Extracted from the skill's YAML frontmatter

---

## 📝 Skill Detail: Synchronized Memo

![Skill Memo](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/introduce/skill-detail-memo.png)

The **Memo Tab** provides a personal note-taking space:
- Attach context, ideas, or reminders to any skill
- Synchronized across sessions via VS Code global state
- Supports bilingual annotations

---

## 📚 Chronicle Manual & Support

![Manual & Support](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/introduce/chronicle-manual.png)

The **Chronicle Manual** hub offers:
1. **Module Specs**: Understand the interconnected logic of Skills, Workflows, and Rules
2. **Chronicle Logs**: Review visual alignment and version history
3. **Space Ops**: Physical interface guidelines for high-intensity coordination

### 🌟 Golden Era Support

Become a **Golden Supporter** to fuel the evolution of the ChronicleCore ecosystem:
- Exclusive **Midnight Gold UI** theme
- **Supporter Badge** in your dashboard
- Unlock future premium features

---

## 🚀 Quick Start

1. **Install the Extension**: Search for `Antigravity: Skills Chronicle` in VS Code Extensions, or install from the Marketplace.
2. **Open the Dashboard**: Click the 📜 icon in the Activity Bar, or use the command palette (`Ctrl+Shift+P` → `Antigravity: Skills Chronicle`).
3. **Add Sample Skills**: Download official sample skills from our [Skills Repository](https://github.com/Zaious/Antigravity-Skills-Chronicle):

```bash
# English
mkdir -p .agent/skills/illustrator && curl -o .agent/skills/illustrator/Skill.md https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/skills/illustrator/en/Skill.md

# 繁體中文
mkdir -p .agent/skills/illustrator && curl -o .agent/skills/illustrator/Skill.md https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/skills/illustrator/zh-TW/Skill.md
```

## 📂 Skill Asset Customization

Each skill can display custom visual branding inside the Antigravity Dashboard:

| Asset | Recommended Size | File Path |
|-------|------------------|---------------------|
| **Avatar** | 128×128 px (1:1) | `{skill}/assets/avatar.png` |
| **Cover** | 1280×720 px (16:9) | `{skill}/assets/cover.png` |

> 💡 **Tip**: You can also upload assets directly via the Dashboard by hovering over the Avatar or Cover area in the Skill detail view.

## 🏗️ Directory Structure

The extension monitors the following directories:

```
your-project/
├── .agent/
│   ├── skills/         # Your AI skill definitions
│   ├── workflows/      # Step-by-step procedures
│   └── rules/          # Agent behavior rules
└── .gemini/
    └── conversations/  # Claude conversation archives
```

## 📜 License

MIT License for community skill templates.  
The core **Antigravity** engine is proprietary.

## 🙏 Acknowledgments

This project includes components from [skills-cli](https://github.com/kcchien/skills-cli) by KC Chien, used under the MIT License. See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for details.

---

<p align="center">Crafted by <b>Zaious</b> · Powered by <b>ChronicleCore / 編年史記工作室</b></p>
