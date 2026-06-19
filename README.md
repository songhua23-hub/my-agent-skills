# My Agent Skills

A collection of Agent Skills for extending AI coding agent capabilities.

## 🚀 Getting Started

This repository is set up to host and manage Agent Skills for various AI coding agents.

### Installation

```bash
# Install all skills from this repository
npx skills add https://github.com/songhua23-hub/my-agent-skills

# Or install to specific agent
npx skills add https://github.com/songhua23-hub/my-agent-skills -a claude-code

# Global installation
npx skills add https://github.com/songhua23-hub/my-agent-skills -g
```

## 📁 Directory Structure

```
my-agent-skills/
├── LICENSE              # MIT License
├── README.md            # This file
├── .gitignore           # Git ignore rules
└── skills/              # Skills directory
    ├── example-skill/
    │   └── SKILL.md
    └── another-skill/
        └── SKILL.md
```

## 🛠️ Creating Your Own Skills

### 1. Create a skill directory

```bash
mkdir -p skills/my-skill
```

### 2. Create SKILL.md

```bash
cat > skills/my-skill/SKILL.md << 'EOF'
---
name: my-skill
description: Brief description of what this skill does
---

# My Skill

Detailed instructions for the agent to follow when this skill is activated.

## When to Use

Describe scenarios where this skill should be used.

## Steps

1. First step
2. Second step
3. Third step
EOF
```

### 3. Test your skill

```bash
# List available skills
npx skills add ./skills --list

# Install locally
npx skills add ./skills --skill my-skill
```

## 📚 Resources

- [Agent Skills Specification](https://agentskills.io)
- [Skills Directory](https://skills.sh)
- [Skills CLI Documentation](https://github.com/vercel-labs/skills)
- [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills)

## 🤖 Supported Agents

Agent Skills are compatible with:
- Claude Code
- Cursor
- GitHub Copilot
- Cline
- OpenCode
- And 68+ other agents

See [Skills CLI](https://github.com/vercel-labs/skills#supported-agents) for the full list.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Create new skills
- Report issues
- Suggest improvements
- Submit pull requests

## 📖 Next Steps

1. Create your first skill in the `skills/` directory
2. Push to GitHub
3. Install using the Skills CLI
4. Share with the community at [skills.sh](https://skills.sh)
