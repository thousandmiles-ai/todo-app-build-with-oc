# Opencode Starter Kit

Clone and open — skills and MCP are pre-configured.

## Setup

```bash
git clone https://github.com/thousandmiles-ai/todo-app-build-with-oc
cd todo-app-build-with-oc
opencode
```

That's it. The following are ready to use:

- **grill-me** skill — turn any un-clear requirement into a clarified one
- **frontend-design** skill — opinionated UI/design guidance
- **Vercel MCP** — deploy and manage Vercel projects from within Opencode

## Install Opencode

**Linux**

```bash
# curl (recommended)
curl -fsSL https://opencode.ai/install | bash

# npm
npm i -g opencode-ai

# bun
bun add -g opencode-ai
```

**Windows**

Opencode recommends using WSL (Windows Subsystem for Linux) for the best experience — it provides better file system performance, full terminal support, and compatibility with the tools Opencode relies on. 

```powershell
# 1. Install WSL (run in PowerShell as Administrator)
wsl --install

# 2. Open your WSL terminal, then install Opencode
curl -fsSL https://opencode.ai/install | bash
```

If you prefer native Windows (without WSL):

```powershell
npm i -g opencode-ai
```

## Install Vercel

Install Vercel CLI: `npm i -g vercel`
Login to Vercel CLI: `vercel login`
Login to MCP Vercel: `opencode mcp auth vercel`
Test everything right: `vercel whoami`

## Structure
```
todo-app-build-with-oc/
├── .agents/
│   └── skills/
│       ├── frontend-design/
│       │   └── SKILL.md
│       └── grill-me/
│           └── SKILL.md
│       └── grilling/
│           └── SKILL.md
├── opencode.json
├── AGENTS.md
└── README.md
```
