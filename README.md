<div align="center">
  <img src="docs/assets/hero-banner.png" alt="SkilloAI Hero Banner" width="1000px">

  # 🧠 SkilloAI 

  ### **The Universal AI Expert System**
  *Transform your IDE into a powerhouse with 2,600+ specialized skills, curated packs, and autonomous workflows.*

  [![Version](https://img.shields.io/badge/version-1.0.3-blueviolet?style=for-the-badge)](https://github.com/skilloai/agent-skills)
  [![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)
  [![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)
  [![Built For](https://img.shields.io/badge/Built%20For-Cursor%20%7C%20Windsurf-blue?style=for-the-badge)](https://cursor.com)

  [Explore Skills](skills/) • [Discover Packs](packs/) • [Run Workflows](workflows/) • [Documentation](docs/)
</div>

---

## ✨ Features

- **🎯 2,600+ Specialized Skills**: Expert instructions for every technical domain imaginable.
- **📦 25 Curated Skill Packs**: Goal-driven collections (e.g., "SaaS Builder", "Security Auditor").
- **⚡ 50 Autonomous Workflows**: Staggered execution plans for complex engineering tasks.
- **🧠 Native AI Unification**: Powered by the `.agent` directory, understood natively by Cursor & Windsurf.
- **🚀 MCP Ready**: Full support for the Model Context Protocol (MCP) to extend AI with live tools.

---

## 🚀 Quick Start

Initialize SkilloAI in your project in seconds using the official CLI.

```bash
# Initialize SkilloAI in the current directory
npx -y skilloai init
```

### 🧠 Core Commands

| Command | Description |
| :--- | :--- |
| `skilloai explore` | Browse 2,600+ skills by category |
| `skilloai packs` | Discover and install curated Skill Packs |
| `skilloai run <prompt>` | Execute AI agents or workflows on your input |
| `skilloai update` | Sync latest content and rebuild local database |
| `skilloai doctor` | Verify installation and runtime health |

---

## 📂 Structure: The `.agent` Directory

SkilloAI uses the `.agent/` directory as its unified runtime. This folder is automatically detected by modern AI-native IDEs.

```bash
.agent/
├── skills/       # 2,600+ specialized instructions
├── packs/        # Curated bundles for specific goals
├── workflows/    # Multi-step execution plans
└── skills-db.json # High-performance offline index
```

---

## 🛠️ Integrated Ecosystem

### 🔌 Running MCP Servers
SkilloAI supports **Model Context Protocol** servers to give your AI real-time tool access.

```bash
# Run standalone using npx/uv
npx -y @modelcontextprotocol/server-everything

# Or run via SkilloAI CLI for integrated reasoning
skilloai run "use the sqlite mcp to analyze user data"
```

### 💻 IDE Integration (Cursor / Windsurf)
SkilloAI is designed to be the "Expert Engine" for your IDE. Once initialized, your AI assistant will automatically leverage the skills in the `.agent` directory to provide high-precision assistance.

---

## 🌟 Contributing

SkilloAI is a community-driven expert system. We welcome new skills, packs, and workflow optimizations!

1.  Check out our **[Contributing Guide](CONTRIBUTING.md)**.
2.  Use the `@skill-creator` skill to build your own expertise.
3.  Submit a Pull Request to share your knowledge with the world.

---

<div align="center">
  <sub>Built with ❤️ by the SkilloAI Community.</sub><br>
  <sub>"Every expert was once a beginner."</sub>
</div>
