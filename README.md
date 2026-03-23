# Taiwan Skills 🇹🇼

**Everything you need for Taiwan — travel, research, local context.**

A growing collection of Taiwan-specific agent skills:

| Skill | Description |
|-------|-------------|
| [taiwan-guide](skills/taiwan-guide) | First-time visitor guide: culture, food, transport, history, hidden gems |
| [taiwan-forum-search](skills/taiwan-forum-search) | Search Taiwan forums (PTT, Dcard, Mobile01, 巴哈姆特) |

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## Installation

### npx skills

```bash
npx skills add git@github.com:mcltyl/taiwan-guide-skills.git
```

### Manually

#### Claude Code

Add the contents of this repo to a `/.claude` folder in your project.

#### OpenCode

```bash
git clone https://github.com/mcltyl/taiwan-guide-skills.git ~/.opencode/skills/taiwan-skills
```

#### OpenClaw

```bash
git clone https://github.com/mcltyl/taiwan-guide-skills.git ~/.openclaw/skills/taiwan-skills
```

---

## Skills Overview

### taiwan-guide

Comprehensive guide for first-time visitors:
- Visa, money, transport, apps
- Food culture and must-try dishes
- Cultural etiquette and do's/don'ts
- Hidden gems locals love
- Historical context

### taiwan-forum-search

Search Taiwan's major online communities:
- **PTT** — News, politics, tech jobs, stock
- **Dcard** — Career, relationships, campus
- **Mobile01** — 3C reviews, cars, home
- **巴哈姆特** — Games, anime, ACG

Use cases:
- Company/interview research
- Product reviews before buying
- Salary benchmarks
- Local sentiment on current events

---

## Quick Reference

### Travel Essentials

| Topic | Quick Answer |
|-------|--------------|
| Visa | 90 days visa-free for most Western countries |
| Currency | NT$ (New Taiwan Dollar). Cash is king. |
| Transport | Get an EasyCard immediately |
| Safety | Very safe. Walk alone at night. |
| Tipping | Not expected |

### Forum Search Patterns

```
# Interview experiences
site:ptt.cc OR site:dcard.tw "[公司名]" 面試

# Product reviews  
site:mobile01.com "[產品]" 開箱

# Salary discussions
site:ptt.cc Tech_Job "[職位]" 年薪
```

---

## Planned Skills

Want these? Let me know or contribute!

- [ ] **taiwan-news** — Monitor Taiwan news sources, summarize current events
- [ ] **taiwan-transport** — Real-time train/bus/HSR info, route planning
- [ ] **taiwan-food** — Restaurant recommendations by area, booking help
- [ ] **taiwan-weather** — Local weather + typhoon tracking
- [ ] **taiwan-jobs** — Job board aggregation (104, 1111, CakeResume)
- [ ] **taiwan-visa** — Immigration rules, ARC/work permit guidance
- [ ] **taiwan-mandarin** — Taiwanese Mandarin specifics, slang, pronunciation
- [ ] **taiwan-politics** — Political context explainer (for understanding news)

---

## Sources

- Taiwan Tourism Bureau
- Forum content (PTT, Dcard, Mobile01, Bahamut)
- Public knowledge, no copyrighted content reproduced

---

## License

MIT

---

## Support

If you find this useful, consider buying me a coffee ☕

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)
