# My Agent Skills

A collection of Agent Skills for extending AI coding agent capabilities.

## 🚀 Available Skills

### find-skills
Helps you discover and install agent skills from the open ecosystem. Perfect for finding specialized tools and workflows.

- **Name**: find-skills
- **Description**: Discover and install agent skills
- **Source**: [vercel-labs/skills](https://github.com/vercel-labs/skills) (MIT License)

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

## 🤖 Supported Agents

These skills are compatible with:
- Claude Code
- Cursor
- GitHub Copilot
- Cline
- OpenCode
- And 68+ other agents

See [Agent Skills CLI](https://github.com/vercel-labs/skills) for full list.

## 📚 Documentation

- [Agent Skills Specification](https://agentskills.io)
- [Skills Directory](https://skills.sh)
- [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills)

## 🎯 Directory Structure

```
my-agent-skills/
├── LICENSE
├── README.md
├── skills/
│   └── find-skills/
│       └── SKILL.md
└── .gitignore
```

## 📖 Credits

**Original Sources:**
- **find-skills** - Adapted from [vercel-labs/skills](https://github.com/vercel-labs/skills)
- **Vercel Labs** - For creating and maintaining the open Agent Skills ecosystem

**Attribution:**
This project includes skills and components from the [vercel-labs/skills](https://github.com/vercel-labs/skills) repository, which is licensed under the MIT License. We appreciate Vercel's contribution to the open-source community.

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What This Means

✅ **You can:**
- Use these skills for any purpose (commercial or non-commercial)
- Modify and adapt the skills
- Distribute copies
- Include in your own projects

⚠️ **You must:**
- Include the original copyright notice
- Include a copy of the license

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Submit new skills
- Report issues
- Suggest improvements
- Fork and create your own versions

## 📞 Support

For issues with the skills, check:
1. [skills.sh](https://skills.sh) - Official skills marketplace
2. [vercel-labs/skills](https://github.com/vercel-labs/skills) - Original repository
3. [Agent Skills Specification](https://agentskills.io) - Technical documentation
