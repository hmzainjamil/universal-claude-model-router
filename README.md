# universal-claude-model-router

> **Universal model router — intelligent routing across Claude, GPT, Gemini, Groq**

![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat)
![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-FF6B35?style=flat)
![Stars](https://img.shields.io/github/stars/hmzainjamil/universal-claude-model-router?style=flat)
![Last Commit](https://img.shields.io/github/last-commit/hmzainjamil/universal-claude-model-router?style=flat)

---

## CONCEPTS

| Concept | Description |
|---|---|
| **Router** | Intelligently selects model based on task |
| **Fallback** | Auto-retry with next model on failure |
| **Cost Control** | Route cheap tasks to fast/cheap models |
| **Latency** | Route time-sensitive tasks to fastest model |
| **Quality** | Route complex tasks to highest-capability model |
| **Load Balance** | Distribute across providers to avoid rate limits |
| **Logging** | Track which model handled each request |
| **Budget** | Hard spend limits per model/day |

---

## 🔥 Hot Commands

```bash
# Activate skill
claude --skill universal-claude-model-router 'your task'

# Quick workflow
claude 'routing automation task'

# Get capabilities
claude 'what can universal-claude-model-router do?'
```

## ■ tip
> Mention **routing** or **model** in your prompt to auto-activate this skill.

---

## ☠️ STARTUPS / BUSINESSES

- **Agencies**: automate routing workflows for clients at scale
- **Founders**: ship model features 10x faster
- **Freelancers**: deliver claude work with AI precision

---

## Features

- Routing automation
- Model automation
- Claude automation
- Gpt automation
- Gemini automation
- Groq automation

---

## Installation

```bash
git clone https://github.com/hmzainjamil/universal-claude-model-router.git
cd universal-claude-model-router
```

---

## Usage

```bash
# Activate skill in Claude Code
claude --skill universal-claude-model-router "your task here"

# Quick workflow
claude "routing automation task"

# Get help
claude "what can universal-claude-model-router do?"
```

---

## Configuration

| Variable | Description | Default |
|---|---|---|
| `API_KEY` | Primary API key | Required |
| `MODEL` | AI model to use | claude-3-5-sonnet |
| `DEBUG` | Enable verbose debug | false |
| `MAX_TOKENS` | Max token budget | 8192 |
| `TIMEOUT` | Request timeout (sec) | 30 |
| `LOG_LEVEL` | Logging verbosity | info |

---

## Architecture

```
universal-claude-model-router/
├── README.md           # Documentation
├── SKILL.md            # Claude Code skill definition
├── scripts/            # Automation scripts
├── templates/          # Output templates
├── examples/           # Usage examples
└── docs/               # Extended documentation
```

---

## Examples

### Basic

```bash
# Simple task
claude --skill universal-claude-model-router "routing task"

# Verbose
claude --skill universal-claude-model-router --verbose "detailed model task"
```

### Advanced Pipeline

```bash
# Chain skills
claude --skill universal-claude-model-router "step 1" | claude --skill summarize

# Batch run
for item in $(cat list.txt); do
  claude --skill universal-claude-model-router "process $item"
done
```

---

## Troubleshooting

| Issue | Cause | Fix |
|---|---|---|
| Auth fails | Invalid API key | Re-export key in shell profile |
| Timeout | Network or large payload | Increase TIMEOUT value |
| Empty output | Prompt too vague | Add more context |
| Rate limit | Too many requests | Add delay between calls |
| Model error | Unsupported version | Update MODEL variable |
| Import error | Missing dependency | Run pip install -r requirements.txt |

---

## Comparison

| Feature | This Skill | Alt A | Alt B |
|---|---|---|---|
| Claude Code native | ✅ | ❌ | ✅ |
| Auto-activation | ✅ | ✅ | ❌ |
| Free to use | ✅ | ❌ | ✅ |
| Production ready | ✅ | ✅ | ❌ |
| Active maintenance | ✅ | ❌ | ❌ |

---

## Changelog

| Version | Changes |
|---|---|
| v2.0 | Claude 4 support, auto-activation |
| v1.5 | Added keyword triggers |
| v1.0 | Initial release |

---

## Contributing

1. Fork → feature branch → commit → PR
2. Follow conventional commits: `feat:`, `fix:`, `docs:`
3. Add tests for new features

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/universal-claude-model-router&type=Date)](https://star-history.com/#hmzainjamil/universal-claude-model-router&Date)

---

## 📜 License

MIT — free to use, modify, distribute.

---

Made with ❤️ by [@hmzainjamil](https://github.com/hmzainjamil)
