# My Agent Skills

A collection of Agent Skills for extending AI coding agent capabilities.

## 🚀 Available Skills

### find-skills
Helps you discover and install agent skills from the open ecosystem. Perfect for finding specialized tools and workflows.

- **Name**: find-skills
- **Description**: Discover and install agent skills
- **Source**: [vercel-labs/skills](https://github.com/vercel-labs/skills)

## 📥 Installation

### Install All Skills

```bash
npx skills add https://github.com/songhua23-hub/my-agent-skills
```

### Install Specific Skill

```bash
npx skills add https://github.com/songhua23-hub/my-agent-skills --skill find-skills
```

### Install to Specific Agent

```bash
npx skills add https://github.com/songhua23-hub/my-agent-skills --skill find-skills -a claude-code
```

### Global Installation

```bash
npx skills add https://github.com/songhua23-hub/my-agent-skills -g
```

## 🔍 Using Skills

Once installed, your coding agent will automatically load these skills. For example, with find-skills:

```bash
npx skills find react
```

## 📚 Supported Agents

These skills are compatible with:
- Claude Code
- Cursor
- GitHub Copilot
- Cline
- OpenCode
- And 68+ other agents

See [Agent Skills CLI](https://github.com/vercel-labs/skills) for full list.

## 📖 Documentation

- [Agent Skills Specification](https://agentskills.io)
- [Skills Directory](https://skills.sh)
- [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills)

## 🛠️ Directory Structure

```
my-agent-skills/
├── README.md
├── skills/
│   └── find-skills/
│       └── SKILL.md
└── .gitignore
```

## 📝 License

MIT
