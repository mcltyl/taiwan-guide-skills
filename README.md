# Taiwan Skills 🇹🇼

**Everything you need for Taiwan — travel, research, local context.**

A growing collection of Taiwan-specific agent skills.

| Skill | Description |
|-------|-------------|
| [taiwan-guide](skills/taiwan-guide) | First-time visitor guide: culture, food, transport, history |
| [taiwan-forum-search](skills/taiwan-forum-search) | Search PTT, Dcard, Mobile01, 巴哈姆特 |
| [taiwan-food](skills/taiwan-food) | Restaurant guide, night markets, regional specialties |
| [taiwan-news](skills/taiwan-news) | Media landscape, bias guide, fact-checking |
| [taiwan-visa](skills/taiwan-visa) | Immigration, work permits, ARC, citizenship |
| [taiwan-politics](skills/taiwan-politics) | Political system, parties, cross-strait context |
| [taiwan-healthcare](skills/taiwan-healthcare) | NHI, hospitals, pharmacies, emergencies |
| [taiwan-slang](skills/taiwan-slang) | PTT terms, internet slang, Taiwanese Mandarin |

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## Installation

### npx skills

```bash
npx skills add git@github.com:mcltyl/taiwan-guide-skills.git
```

### Manually

```bash
# OpenClaw
git clone https://github.com/mcltyl/taiwan-guide-skills.git ~/.openclaw/skills/taiwan-skills

# OpenCode
git clone https://github.com/mcltyl/taiwan-guide-skills.git ~/.opencode/skills/taiwan-skills

# Claude Code
# Add to /.claude folder in your project
```

---

## Skills Overview

### Living & Daily Life

| Skill | What It Covers |
|-------|---------------|
| **taiwan-food** | Night markets, breakfast shops, regional dishes, dietary restrictions, how to order |
| **taiwan-healthcare** | NHI system, finding doctors, pharmacies, emergencies, costs |
| **taiwan-slang** | PTT culture, internet expressions, Taiwanese Mandarin, youth slang |

### Research & Context

| Skill | What It Covers |
|-------|---------------|
| **taiwan-forum-search** | How to search PTT, Dcard, Mobile01, 巴哈姆特 |
| **taiwan-news** | Media sources, political bias, fact-checking, how to read critically |
| **taiwan-politics** | Parties, identity politics, cross-strait relations, historical context |

### Immigration & Travel

| Skill | What It Covers |
|-------|---------------|
| **taiwan-guide** | Complete first-time visitor guide |
| **taiwan-visa** | Visa types, work permits, ARC, APRC, citizenship pathways |

---

## Design Principles

These skills are built as **frameworks**, not **databases**:

- ✅ Teach you **how to find** current information
- ✅ Explain **how to interpret** what you find
- ✅ Point to **official sources** for verification
- ❌ Don't contain **fixed data** that goes stale

**Always verify** important information with official sources.

---

## Quick Reference

### Emergency Numbers

| Number | Service |
|--------|---------|
| 119 | Ambulance & Fire |
| 110 | Police |
| 1922 | CDC Hotline |

### Essential Terms

| Term | Meaning |
|------|---------|
| 捷運 | MRT (metro) |
| 便當 | Lunch box |
| 健保卡 | NHI card |
| 推/噓 | Upvote/downvote (PTT) |
| 歹勢 | Sorry (Taiwanese) |

### Political Shorthand

| Color | Party |
|-------|-------|
| 🟢 綠 | DPP 民進黨 |
| 🔵 藍 | KMT 國民黨 |
| ⚪ 白 | TPP 民眾黨 |

---

## Planned Skills

Want these? Open an issue or contribute!

- [ ] **taiwan-transport** — Real-time train/bus/HSR info
- [ ] **taiwan-banking** — Opening accounts, payments
- [ ] **taiwan-housing** — Rental system, 591, contracts
- [ ] **taiwan-telecom** — Phone plans, SIM cards
- [ ] **taiwan-shopping** — E-commerce, convenience stores
- [ ] **taiwan-holidays** — Calendar, customs
- [ ] **taiwan-emergency** — Detailed emergency procedures

---

## Contributing

Found something outdated? Know a better way to explain something? PRs welcome!

---

## License

MIT

---

## Support

If you find this useful, consider buying me a coffee ☕

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)
