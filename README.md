# 🏛️ career-projects-and-case-studies

This repository showcases commercial-grade web platforms, distributed AI workflows, and enterprise design engines built for live production environments. 

Each case study breaks down system architecture, core engineering challenges, technical stacks, and production outcomes.

---

## 📋 Table of Contents
1. [QuickGrid — Vector Translation Engine & Figma Plugin](#1-quickgrid--vector-translation-engine--figma-plugin)
2. [Vibe — Autonomous AI Web Provisioning Engine](#2-vibe--autonomous-ai-web-provisioning-engine)
3. [Terapage — Collaborative AI Research Workspace](#3-terapage--collaborative-ai-research-workspace)
4. [54 Crates — High-Throughput Media Platform](#4-54-crates--high-throughput-media-platform)

---

## 1. QuickGrid — Vector Translation Engine & Figma Plugin
* **Production URL:** [quickgrid.ai](https://staging-quickgridai-dashboard.axtrastudios.com/)
* **Domain:** Creative Tech / Canvas Rendering / Figma Extensions
* **Tech Stack:** `React.js` `TypeScript` `Node.js` `Figma Plugin API` `Abstract Syntax Trees (AST)`

### 🛠️ Architecture & Core Engineering
```mermaid
flowchart LR
    A[Figma Canvas Node] -->|Figma Plugin API| B[AST Node Parser & Normalizer]
    B -->|JSON Payload| C[Express / Node Backend]
    C -->|Layout Spec| D[QuickGrid Canvas Engine]
    D -->|60 FPS Render| E[Browser Viewport]
