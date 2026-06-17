<div align="center">

# Design Assets Index 🎨

A curated external resource index of ready-made design assets — stock photos, icons, fonts, color palettes, mockups, UI kits, and templates.

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

**中文说明** · [English](README.md)

</div>

---

## Why

When you ask an agent for "a nice placeholder image" or "an icon set for a sidebar", how-to design skills tell it the *principles* — but not *which site to grab from*. This skill fills that gap: a navigable catalog of trustworthy asset sources, distilled from the [awesome-design](https://github.com/gztchan/awesome-design) and [design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers) awesome-lists.

> 💡 **Type note:** This is a *resource index* skill (links + one-line notes). It is deliberately not a how-to/teaching skill.

## What's inside

Each entry is `Name (link) — one-line note`. Seven categories, 8 curated picks each (+ extras in `references/more.md`):

- 🖼️ Stock photos
- 🎯 Icons
- 🔤 Fonts
- 🎨 Color palettes
- 📱 Mockup
- 🧩 UI Kit
- 📄 Templates

## Install

```bash
git clone https://github.com/Ezra-Y/design-assets-index.git ~/.claude/skills/design-assets-index
```

Then restart Claude Code (or run `/reload-plugins`).

## Use

Auto-triggers on phrases like "找素材 / 免费 image / icon library / 字体 / 配色 / Mockup / UI Kit". Examples:

```
I need an icon set for a sidebar — what are good sources?
帮我找几个免费的高质量图库
Give me a few UI kits to reference
```

## Structure

```
design-assets-index/
├── SKILL.md              # main index (≤100 lines)
├── references/
│   └── more.md           # extra entries
└── README.md
```

## Sources & Attribution

Curated and condensed from (please star the originals):

- [gztchan/awesome-design](https://github.com/gztchan/awesome-design)
- [bradtraversy/design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers)

More awesome lists at [sindresorhus/awesome](https://github.com/sindresorhus/awesome).

## License

[MIT](LICENSE) — © Ezra-Y
