# 🧠 Brain Skill

A reusable AI coding skill that gives your AI assistant persistent project memory, architectural awareness, and token-efficient workflows.

Instead of repeatedly scanning your entire project, the AI maintains a structured **Brain** that stores architecture, coding patterns, design decisions, and session history.

---

## Installation

### Option 1 — Clone the repository (Recommended)

```bash
git clone https://github.com/Sumi-tgupta/brain-skill.git
```

Copy the file into your project's skills directory:

```
your-project/
└── .AGENT/
    └── skills/
        └── brain.md
```

---

### Option 2 — Download

1. Open `brain.md`
2. Copy its contents
3. Create the following file inside your project:

```
.AGENT/
└── skills/
    └── brain.md
```

Paste the contents and save.

---

## Folder Structure

Your project should look like this:

```
your-project/
│
├── src/
├── package.json
├── README.md
│
└── .AGENT/
    └── skills/
        └── brain.md
```

---

## What Happens Next?

When your AI assistant reads `brain.md`, it automatically initializes a project brain.

```
brain/
├── architecture.md
├── patterns.md
├── decisions.md
└── memory.md
```

These files become the AI's long-term understanding of your project.

---

## Features

* Persistent AI memory
* Token-efficient workflow
* Architecture documentation
* Git-style change tracking
* Session-aware development
* Architecture Decision Records (ADR)
* Coding conventions management
* Automatic project knowledge updates

---

## Supported AI Assistants

Any AI coding assistant capable of following project instructions, including:

* ChatGPT
* Claude
* Gemini
* Cursor
* Windsurf
* GitHub Copilot
* Continue
* Cline
* Roo Code

---

## Built-in Commands

| Command             | Description                          |
| ------------------- | ------------------------------------ |
| `/status`           | Show completed and pending tasks     |
| `/brain-sync`       | Check consistency of all brain files |
| `/what-next`        | Suggest the next development task    |
| `/decision <title>` | Record a new architecture decision   |
| `/checkpoint`       | Force a complete brain update        |

---

## Philosophy

> **Read the brain. Do the work. Update the brain.**

The code is the implementation.

The brain is the understanding.

---

## License

MIT License
