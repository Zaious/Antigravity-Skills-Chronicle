<div align="center">

# 🌌 Antigravity: Skills Chronicle

**The premium management layer for AI Skills, powered by the ChronicleCore system.**

[![VS Code](https://img.shields.io/badge/VS%20Code-Extension-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://marketplace.visualstudio.com/items?itemName=ChronicleCore.antigravity-skills-chronicle)
[![Brand](https://img.shields.io/badge/Brand-ChronicleCore-B91C1C?style=for-the-badge)](https://buymeacoffee.com/zaious)

</div>

---

*Manage your AI Skills, Workflows, and Rules with a premium visual dashboard.*

## 🚀 Features

| Feature | Description |
|---------|-------------|
| **📁 Skills Dashboard** | View and manage all skills in your `.agent/skills/` directory |
| **⚙️ Workflow Manager** | Organize and execute workflows from `.agent/workflows/` |
| **🛡️ Rules Inspector** | View and edit agent rules |
| **🕰️ Conversation Archive** | Browse and search past Claude conversations |
| **📊 Dynamic Status Bar** | Real-time skill and workflow count in the status bar |

---

## 🏗️ Repository Structure Guide

To help contributors navigate the project, the repository is structured functionally. **Only specific files are bundled into the final VS Code Extension (`.vsix`)**.

### 📦 1. Bundled (The VS Code Extension)
What users actually download from the Marketplace:
- `README.md` & `LICENSE` & `THIRD-PARTY-NOTICES.md`
- `package.json` (Extension manifest & commands)
- `docs/` & `public/` (EXCLUDED via .vscodeignore)
- `out/` (Compiled backend extension logic)
- `web/dist/` (Compiled frontend React UI)
- `resources/` (Icons and branding assets)

### 🌐 2. Public Repository (GitHub Only)
Assets meant for developers and documentation:
- `docs/`: Technical documents, architecture plans, and legacy scripts.
- `public/assets/`: High-res screenshots and media for this README.
- `web/`: The raw React/Vite frontend source code.
- `src/`: The raw TypeScript backend source code.

### 💻 3. Monitored Workspaces (User's Local Machine)
Once installed, the extension monitors these folders in the user's workspace:

```text
your-project/
├── .agent/
│   ├── skills/         # AI skill definitions (SKILL.md)
│   ├── workflows/      # Step-by-step procedures
│   └── rules/          # Agent behavior logic
└── .gemini/
    └── conversations/  # Conversation archives & history
```

---

## 🌍 Global Path Configuration

You can configure global asset paths in the **Terminal Dashboard**.

**Default Global Paths:**
- Skills: `~/.gemini/antigravity/global_skills`
- Workflows: `~/.gemini/antigravity/global_workflows`
- Rules: `~/.gemini/antigravity/global_rules`

*(Note: Antigravity official is continuously adjusting the global paths, please check the dashboard for the latest configuration options.)*

---

## 📊 Status Bar Integration

![Status Bar](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Public/main/introduce/status-bar.png)

The extension provides a **real-time status bar** showing your current asset counts.

---

## 🖥️ Terminal Dashboard

![Terminal](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Public/main/introduce/dashboard-full.png)

The **Terminal View** is your command center.

---

## 📁 Skill Detail: File Browser

![Skill Files](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Public/main/introduce/skill-detail-files-2.png)

Explore the internal structure of any skill.

---

## ⚙️ Skill Detail: Configuration View

![Skill Config](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Public/main/introduce/skill-detail-config-2.png)

The **Configuration Tab** displays the parsed Chronicle Node Schema.

---

## 📝 Skill Detail: Synchronized Memo

![Skill Memo](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Public/main/introduce/skill-detail-memo-2.png)

The **Memo Tab** provides a personal note-taking space.

---

## 📚 Chronicle Manual & Support

![Manual & Support](https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Public/main/introduce/manual-overview.png)

The **Chronicle Manual** hub offers module specs, chronicle logs, and space ops guidelines.

### 🌟 Golden Era Support

Become a **Golden Supporter** to fuel the evolution of the ChronicleCore ecosystem:
- Exclusive **Midnight Gold UI** theme
- **Supporter Badge** in your dashboard
- Unlock future premium features

---

<div align="center">

**Made with ❤️ by ChronicleCore / 編年史記工作室**

</div>
