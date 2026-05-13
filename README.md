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

This repository is designed to be **autonomous**. If you use a compatible AI editor (like Cursor), you no longer need to manually prompt the AI to read the memory.

### Automated Workflow (Recommended)
1.  **Cursor Editor**: The `.cursorrules` file at the root automatically instructs the AI to read and update the `/memory` directory.
2.  **Proactive Learning**: The model is instructed to log all mistakes in `lessons.md` so it never repeats them.
3.  **Automatic State Sync**: After completing a task, the model will update `tasks.md` and `progress.md` without being told.

### Manual Initialization (If needed)
If you are using a tool that doesn't support automatic rules, use this system prompt:
> **"Read the /memory folder first to understand the project state and past lessons. Follow the rules in memory/rules.md. After every task, update tasks.md, progress.md, and log any mistakes or new learnings in lessons.md. You are responsible for keeping this memory synchronized."**

---

## ✨ Key Advantages
* **Zero Context Loss:** Seamlessly transition between different AI models.
* **Proactive Correction:** The model "trains" itself by recording its own mistakes.
* **Autonomous Maintenance:** Memory updates happen in the background as part of the AI's workflow.
* **Model Agnostic:** Works with any LLM (GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro, DeepSeek).
* **Version Controlled:** Since the memory is stored in Markdown, every update is tracked via Git, providing a clear history of project evolution.

---
**Maintained by [Atul Sharma](https://github.com/kumarsharmaatul)**
