---
title: Model Context Protocol (MCP)
tags:
  - ai
  - protocol
  - context
  - automation
date: 2026-05-28
aliases: []
id: mcp
---

# Model Context Protocol (MCP)

The **Model Context Protocol (MCP)** is an open-source standard introduced by Anthropic in late 2024. It aims to solve the integration challenge between AI models and various data sources or tools, often described as the **"USB-C port for AI."**

## Core Concepts

MCP establishes a standardized way for AI applications (hosts) to communicate with external data and services (servers).

### 1. Architecture
- **MCP Host:** The AI environment (e.g., Claude Desktop, VS Code, or a custom app).
- **MCP Client:** The component within the host that handles connections.
- **MCP Server:** A lightweight service exposing specific data or tools (e.g., GitHub, Google Drive, or a local database).

### 2. Main Capabilities
- **Resources:** Read-only data accessible to the AI (files, API docs, database schemas).
- **Tools:** Executable functions the AI can call (sending emails, running SQL, creating tickets).
- **Prompts:** Reusable templates for complex workflows or specialized interactions.

## Why It Matters

- **Standardization:** One integration works across multiple AI models and platforms.
- **Security:** Provides granular control over what data and tools are exposed to the AI.
- **Accuracy:** Reduces hallucinations by providing models with real-time, grounded context from actual data sources.

## Ecosystem

The MCP ecosystem is rapidly growing, with a community-driven repository of servers for popular services like:
- GitHub / GitLab
- Google Drive / Slack / Notion
- PostgreSQL / SQLite
- Local File-system / Terminal

For more information, visit the official documentation at [modelcontextprotocol.io](https://modelcontextprotocol.io).

---
**Related Notes:**
- [[Archive/GEMINI]]
- [[codex]]
