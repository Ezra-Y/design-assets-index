<div align="center">

# 设计素材索引 🎨

精选的设计素材外部资源索引——图库、图标、字体、配色板、Mockup、UI Kit、模板。

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[English](README.md) · 中文

</div>

---

## 为什么需要它

当你问 agent「给我个占位图」「找个侧边栏图标集」时，how-to 类设计 skill 只告诉你*原则*，不告诉你*去哪个站找*。这个 skill 补上这一环：从 awesome-design 与 design-resources-for-developers 两个 awesome-list 精选的可导航素材目录。

> 💡 **类型说明**：这是*资源索引* skill（链接 + 一句话说明），不是 how-to/教学 skill。

## 内容

每个条目为「名称（链接）— 一句话说明」。`SKILL.md` 是**调度索引**：每类 2–3 条精选内联，完整列表在按分类的 reference 文件（按需读取 / loaded on demand）：

- 🖼️ 图库素材 → `references/stock-photos.md`
- 🎯 图标 → `references/icons.md`
- 🔤 字体 → `references/fonts.md`
- 🎨 配色 → `references/color-palettes.md`
- 📱 Mockup → `references/mockups.md`
- 🧩 UI Kit → `references/ui-kits.md`
- 📄 模板 → `references/templates.md`

## 安装

```bash
git clone https://github.com/Ezra-Y/design-assets-index.git ~/.claude/skills/design-assets-index
```

然后重启 Claude Code（或跑 `/reload-plugins`）。

## 用法

在「找素材 / 免费 image / icon library / 字体 / 配色 / Mockup / UI Kit」等表述时自动触发。示例：

```
帮我找几个免费的高质量图库
I need an icon set for a sidebar — what are good sources?
给我几个现成的 UI Kit 参考
```

## 结构

```
design-assets-index/
├── SKILL.md              # 调度索引：每类 2-3 精选 + 指针
├── references/           # 按分类的完整列表（按需读取）
│   ├── stock-photos.md
│   ├── icons.md
│   ├── fonts.md
│   ├── color-palettes.md
│   ├── mockups.md
│   ├── ui-kits.md
│   └── templates.md
└── README.md
```

## 来源与致谢

本 skill 的数据来自以下两个 awesome-list，经精选、精简、翻译而成；原列表收录更全、更新更勤，建议给原仓库点 star：

- [gztchan/awesome-design](https://github.com/gztchan/awesome-design) — Awesome Design 合集，含 Stock / Color / Icon and Logo / Typography / Mockup 等分类。
- [bradtraversy/design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers) — Brad Traversy 维护的开发者向免费设计资源合集。

更多 awesome 列表见 [sindresorhus/awesome](https://github.com/sindresorhus/awesome)。

## License

[MIT](LICENSE) — © Ezra-Y
