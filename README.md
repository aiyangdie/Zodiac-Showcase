# ✨ 星座奥秘 — Zodiac Showcase

> 探索十二星座的神奇特质 — 沉浸式星空互动展示

📌 **项目简介**

星座奥秘是一个以星空为主题的十二星座互动展示网站，将星座按火、土、风、水四大元素分类呈现。项目采用深色宇宙背景搭配动态星空、闪烁星星和流星效果，每张星座卡片配有专属图标、基本信息、性格特征和代表元素，悬停时呈现发光与上浮动画，营造出神秘而浪漫的浏览体验。

✨ **核心特性**

- 🌌 **动态星空背景** — 三层叠加：移动星星 + 闪烁层 + 流星层
- ☄️ **流星划过效果** — JavaScript 动态生成，随机位置与速度
- 🔥🌍💨💧 **四元素分类** — 火象 / 土象 / 风象 / 水象，各具专属配色与发光边框
- 🃏 **星座详情卡片** — 基本信息 + 性格特征 + 代表元素，结构化展示
- ✨ **丰富悬停动画** — 卡片上浮缩放、图标旋转放大、光扫效果
- 🎨 **元素专属配色** — 火(红) / 土(绿) / 风(蓝) / 水(青)，渐变边框 + 发光阴影
- 📜 **Noto Serif SC 字体** — 衬线中文字体，典雅东方韵味
- 📱 **响应式网格** — 4 列 → 3 列 → 2 列 → 1 列，全设备适配
- 🎭 **浮动呼吸动画** — 卡片持续 `float` 动画，交错延迟

🛠️ **技术栈**

| 技术 | 说明 |
|------|------|
| HTML5 | 语义化结构 |
| CSS3 | Grid、`backdrop-filter`、渐变、动画、CSS Variables |
| JavaScript | 流星生成、版权年份自动更新 |
| Font Awesome 6.0 | 星座与元素图标 |
| Noto Serif SC | Google Fonts 衬线中文字体 |

🚀 **快速开始**

**前置条件**

- 现代浏览器（Chrome / Firefox / Safari / Edge）

**安装步骤**

```bash
git clone https://github.com/aiyangdie/Zodiac-Showcase.git
cd Zodiac-Showcase
```

**运行**

直接在浏览器中打开 `index.html`，或启动本地服务器：

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

访问 `http://localhost:8000`

📂 **项目结构**

```
Zodiac-Showcase/
├── index.html          # 主页面（四大元素分类 + 12 星座卡片）
├── styles.css          # 全局样式（星空背景 + 卡片动画 + 响应式）
├── script.js           # 流星效果 + 版权年份
├── .gitignore          # Git 忽略配置
├── CNAME               # GitHub Pages 自定义域名
├── README.md           # 项目说明（中文）
├── README_zh.md        # 项目说明（中文副本）
└── README_en.md        # 项目说明（英文，如存在）
```

🤝 **贡献与许可证**

欢迎提交 Issue 和 Pull Request 改进项目！

本项目基于 **MIT License** 开源 — 详见 [LICENSE](LICENSE) 文件。

用 ❤️ 和 ✨ 制作
