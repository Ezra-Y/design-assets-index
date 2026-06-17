<div align="center">

# 设计素材索引 🎨

精选的设计素材外部资源索引——图库、图标、字体、配色板、Mockup、UI Kit、模板。

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[English](README.md) · 中文说明

</div>

---

## 为什么需要它

当你问 agent「给我个占位图」「找个侧边栏图标集」时，how-to 类设计 skill 只告诉你*原则*，不告诉你*去哪个站找*。这个 skill 补上这一环：从 awesome-design 与 design-resources-for-developers 两个 awesome-list 精选的可导航素材目录。

> 💡 **类型说明**：这是*资源索引* skill（链接 + 一句话说明），不是 how-to/教学 skill。

## 内容

每个条目为「名称（链接）— 一句话说明」。七个分类，每类 8 个精选（更多见 `references/more.md`）：

- 🖼️ 图库素材
- 🎯 图标
- 🔤 字体
- 🎨 配色
- 📱 Mockup
- 🧩 UI Kit
- 📄 模板

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
├── SKILL.md              # 索引主体（≤100 行）
├── references/
│   └── more.md           # 溢出条目
└── README.md
```

## 来源与致谢

内容精选、精简自以下两个 awesome-list（请给原仓库点 star）：

- [gztchan/awesome-design](https://github.com/gztchan/awesome-design)
- [bradtraversy/design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers)

更多 awesome 列表见 [sindresorhus/awesome](https://github.com/sindresorhus/awesome)。

## License

[MIT](LICENSE) — © Ezra-Y
