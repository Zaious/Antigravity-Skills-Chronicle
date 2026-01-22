# 🏛️ Antigravity: Skills Hub (V1.0)

[English](#english) | [繁體中文](#繁體中文)

<a href="https://www.buymeacoffee.com/zaious"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=☕&slug=zaious&button_colour=FF5F5F&font_colour=ffffff&font_family=Cookie&outline_colour=000000&coffee_colour=FFDD00" /></a>

---

<div id="english">

## English

**Antigravity** is a premium management layer for AI Skills. This repository provides the **V1.0 Reference Assets**, showcasing the dual-layer architecture of Skills and Workflows.

### 🧩 Showcase Assets (V1.0 Community Edition)
- **`illustrator` (Glyph)**: Focuses on **[Visual Translation]**. Transmutes abstract specifications into SVG geometric paths and assets.
- **`vibe-coder` (Vibe Whisperer)**: Focuses on **[Intent Parsing]**. Decodes vague "feelings" into clear, actionable development directives.

### 🎮 Hidden Quest: The Lost Portrait
While the Vibe Whisperer possesses the wisdom to perceive intent, they have **lost their own face** (you will find they lack an Avatar image upon download).
> **Your Mission**: Download both experts and try invoking the "illustrator" to draw a portrait that matches the Vibe Whisperer's aura.

### 🚀 Quick Start
1. **Install the Extension**: Install `Antigravity` in your VS Code environment.
2. **One-Click Samples**: Run the following from your project root:
   ```bash
   # Add Sample Skills (English)
   mkdir -p .agent/skills/illustrator && curl -o .agent/skills/illustrator/Skill.md https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/skills/illustrator/en/Skill.md
   mkdir -p .agent/skills/vibe-coder && curl -o .agent/skills/vibe-coder/Skill.md https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/skills/vibe-coder/en/Skill.md
   ```
3. **Connect**: Open the Antigravity Dashboard to begin your quest.

### 🚀 Standardized structure
Every Antigravity asset follows a strict YAML-powered metadata standard for deep UI integration:
```yaml
# Skill.md (Specification)
name: [Asset Name]
version: [Semantic Version]
capabilities: [Automated Extraction Points]
tags: [Smart Categorization]

# Workflow.md (Operational Procedure)
---
description: [High-level summary of the sequence]
---
```

---

</div>

<div id="繁體中文">

## 繁體中文

**Antigravity** 是專業級的 AI 技能管理介面。本倉庫提供 **V1.0 示範資產**，展示了技能 (Skill) 與工作流 (Workflow) 的雙層核心架構。

### 🧩 核心示範 (V1.0 Community Edition)
- **「畫靈」(`illustrator`)**: 專注於 **[視覺轉譯]**。能將抽象的技術規格轉化為 SVG 幾何路徑與視覺資產。
- **「靈喻師」(`vibe-coder`)**: 專注於 **[意圖解析]**。能聽懂模糊的「感覺 (Vibe)」，將其蒸餾為清晰的開發指令。

### 🎮 隱藏任務 (Hidden Quest): 尋找失落的肖像
靈喻師雖然擁有看穿意圖的智慧，但他卻**遺失了自己的面貌**（下載後你會發現他沒有 Avatar 圖片）。
> **你的任務**：下載這兩位專家，並嘗試命令「畫靈」為「靈喻師」繪製一張符合其氣質的肖像。

### 🚀 快速上手
1. **安裝插件**: 在 VS Code 中安裝 `Antigravity` 擴展。
2. **一鍵載入雙專家**: 在專案根目錄執行以下指令：
   ```bash
   # 載入 [畫靈] 與 [靈喻師] (繁體中文)
   mkdir -p .agent/skills/illustrator && curl -o .agent/skills/illustrator/Skill.md https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/skills/illustrator/zh-TW/Skill.md
   mkdir -p .agent/skills/vibe-coder && curl -o .agent/skills/vibe-coder/Skill.md https://raw.githubusercontent.com/Zaious/Antigravity-Skills-Chronicle/main/skills/vibe-coder/zh-TW/Skill.md
   ```
3. **連通**: 開啟儀表板 (Dashboard)，開始您的任務。

### 🚀 標準化架構 (Specifications)
所有 Antigravity 資產均採用標準 YAML 元數據結構，確保與系統完美整合：
```yaml
# Skill.md (技能規約)
name: [資產名稱]
version: [版本號]
capabilities: [自動化能力提取點]
```

---

</div>

## ⚖️ License
MIT License for community templates. The core **Antigravity** engine is proprietary.

---
<p align="center">Crafted by <b>Zaious</b> • Powered by <b>Antigravity Core</b></p>
