# Design Assets Index 🎨

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](https://github.com/Ezra-Y/design-assets-index)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A curated **external resource index** of ready-made design assets — stock photos, icons, fonts, color palettes, mockups, UI kits, and templates. It tells your coding agent **where to find** assets, not how to design.

精选的**设计素材外部资源索引**——图库、图标、字体、配色板、Mockup、UI Kit、模板。告诉 agent「去哪找」现成素材，而非教如何设计。

---

## Why / 为什么需要它

When you ask an agent for "a nice placeholder image" or "an icon set for a sidebar", how-to design skills tell it the *principles* — but not *which site to grab from*. This skill fills that gap: a navigable catalog of trustworthy asset sources, distilled from the [awesome-design](https://github.com/gztchan/awesome-design) and [design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers) awesome-lists.

当你问 agent「给我个占位图」「找个侧边栏图标集」时，how-to 类设计 skill 只告诉你*原则*，不告诉你*去哪个站找*。这个 skill 补上这一环：从 awesome-design 与 design-resources-for-developers 两个 awesome-list 精选的可导航素材目录。

> 💡 **Type note / 类型说明**: This is a *resource index* skill (links + one-line notes). It is deliberately not a how-to/teaching skill.

---

## What's inside / 内容

Each entry is `Name (link) — one-line note`. Seven categories, 8 curated picks each (+ extras in `references/more.md`):

每个条目为「名称（链接）— 一句话说明」。七个分类，每类 8 个精选（更多见 `references/more.md`）：

- 🖼️ **图库素材 / Stock photos**
- 🎯 **图标 / Icons**
- 🔤 **字体 / Fonts**
- 🎨 **配色 / Color palettes**
- 📱 **Mockup**
- 🧩 **UI Kit**
- 📄 **模板 / Templates**

---

## Install / 安装

### Claude Code (skill)

```bash
# clone into your skills directory
git clone https://github.com/Ezra-Y/design-assets-index.git ~/.claude/skills/design-assets-index
```

Then restart Claude Code (or run `/reload-plugins`).

### As a plugin

```
/plugin marketplace add Ezra-Y/design-assets-index
/plugin install design-assets-index@design-assets-index
```

把仓库 clone 到你的 skills 目录即可。安装后重启 Claude Code（或跑 `/reload-plugins`）。

---

## Use / 用法

The skill auto-triggers on phrases like "找素材 / 免费 image / icon library / 字体 / 配色 / Mockup / UI Kit". Examples:

该 skill 在「找素材 / 免费 image / icon library / 字体 / 配色 / Mockup / UI Kit」等表述时自动触发。示例：

```
帮我找几个免费的高质量图库
I need an icon set for a sidebar — what are good sources?
给我几个现成的 UI Kit 参考
```

---

## Structure / 结构

```
design-assets-index/
├── SKILL.md              # 索引主体（≤100 行）
├── references/
│   └── more.md           # 溢出条目
└── README.md             # 本文件
```

---

## Sources & Attribution / 来源与致谢

Curated, condensed, and translated from two awesome-lists (please star the originals):

内容精选、精简并翻译自以下两个 awesome-list（请给原仓库点 star）：

- [gztchan/awesome-design](https://github.com/gztchan/awesome-design)
- [bradtraversy/design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers)

More awesome lists at [sindresorhus/awesome](https://github.com/sindresorhus/awesome).

---

## License

[MIT](LICENSE) — © Ezra-Y
