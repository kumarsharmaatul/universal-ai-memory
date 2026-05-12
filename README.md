# 🧠 Universal AI Memory

**Universal AI Memory** is a standardized, markdown-based framework designed to maintain long-term project context and continuity across various AI agents (e.g., GPT, Claude, Gemini). By utilizing a dedicated memory layer, this repository eliminates "context loss" when switching between different AI models or development sessions.

---

## 🎯 The Vision
Modern AI development often suffers from fragmented context. When you move from one session to another—or switch tools (from Cursor to Windsurf, for example)—the AI loses the intricate details of your project. This repository acts as a **Persistent Memory Layer**, ensuring that any AI agent can instantly "onboard" itself and understand the current state, rules, and history of the project.

## 📂 Memory Structure

All core context is stored within the `/memory` directory. Each file serves a specific functional purpose:

| File Name | Description |
| :--- | :--- |
| **`project.md`** | High-level project overview, core objectives, and vision. |
| **`architecture.md`** | System design, data flow diagrams, and structural logic. |
| **`stack.md`** | Technical specifications, frameworks, and dependency details. |
| **`rules.md`** | Coding standards, operational constraints, and best practices. |
| **`tasks.md`** | Roadmap and tracking for pending, active, and completed tasks. |
| **`progress.md`** | Log of development milestones and historical updates. |
| **`bugs.md`** | Dedicated tracker for known issues and their resolved fixes. |
| **`decisions.md`** | Documentation of key architectural and logical choices. |
| **`lessons.md`** | Insights, self-corrections, and model training notes. |
| **`prompts.md`** | Optimized system prompts and interaction templates. |

## 🛠️ Usage Guidelines
**Prompt-: **
**Read the /memory folder before starting work.
Update memory files after completing tasks.**

To ensure maximum efficiency when working with an AI assistant (like **Max**), follow these protocols:

1. **Initialization:** Always instruct the AI to read the `/memory` directory at the start of a session to sync with the current project state.
2. **Real-time Updates:** After completing a significant task, the AI should update the relevant files (e.g., `tasks.md` and `progress.md`) to reflect the changes.
3. **Decision Logging:** Any change in logic or strategy must be recorded in `decisions.md` to prevent future regressions.

## ✨ Key Advantages
* **Zero Context Loss:** Seamlessly transition between different AI models without re-explaining project details.
* **Model Agnostic:** Works with any LLM (GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro, DeepSeek).
* **Version Controlled:** Since the memory is stored in Markdown, every update is tracked via Git, providing a clear history of project evolution.

---
**Maintained by [Atul Sharma](https://github.com/kumarsharmaatul) & Max (AI Assistant)**
