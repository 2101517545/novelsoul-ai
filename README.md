# NovelSoul AI · 灵韵AI

多Agent协作驱动的AI小说"人味"注入引擎
Multi-Agent Collaborative Novel Humanizer

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License">
  <img src="https://img.shields.io/badge/AI-Powered-blue" alt="AI Powered">
  <img src="https://img.shields.io/badge/Agents-4+-purple" alt="Agents 4+">
  <img src="https://img.shields.io/badge/Type-Frontend-orange" alt="Frontend">
</p>

---

## ✨ 功能特性

- 🔍 **文本诊断** — 输入AI小说片段，自动检测"没人味"的三维指标（情感缺失率/对话机械度/节奏单一性），生成雷达图诊断报告
- 🎭 **多Agent协作润色** — 4个专职Agent（情感分析师→对话导演→节奏控制师→风格润色师）逐步处理文本，实时展示中间结果
- 📈 **情感曲线图谱** — 润色前后情感波动对比，热力条与图表联动，量化展示"呼吸感"变化
- 📝 **对比审稿台** — 12处修改逐处标注，悬浮显示修改原因和对应Agent署名
- 🎨 **风格迁移** — 支持余华·冷峻 / 村上春树·疏离 / 金庸·武侠 / 通用文学四种风格模板

---

## 🤖 AI技术架构

用户输入 → 文本诊断 → 情感分析师 → 对话导演 → 节奏控制师 → 风格润色师 → 主编审稿 → 最终输出

↓↓↓↓
情感标注层 对话层+潜台词 节奏层+留白 风格统一+终稿

---

```text
**核心架构：多Agent协作 + 长链推理**

- **长链推理**: 文本不一次性重写，而是经过"诊断→拆解→注入→统稿"四阶段推理链，每阶段有明确的输入输出约束
- **多Agent协作**: 4个专职Agent通过结构化中间产物传递上下文，后置Agent可追溯前置Agent的全部决策理由
- **可解释性输出**: 每处修改标注类型、原因和对应Agent，实现AI编辑流程的透明化
```

---

## 🚀 快速开始

1.  克隆仓库：
    ```bash
    git clone https://github.com/foreverida/novelsoul-ai.git
    ```
2.  打开 `index.html`
3.  点击"开始诊断"体验完整流程

> 无需安装任何依赖，无需后端服务，纯浏览器运行。

---

## 🖼️ 截图

| 首页 | 文本诊断 | Agent润色 |
|------|---------|-----------|
| <img width="2840" height="1568" alt="image" src="https://github.com/user-attachments/assets/021ac3fc-6eb3-4ad4-9b8f-badf96fbe592" />|<img width="2842" height="1546" alt="image" src="https://github.com/user-attachments/assets/235cb8bc-9fd8-48b2-8c49-32ddd5a37c38" />|<img width="2842" height="1540" alt="image" src="https://github.com/user-attachments/assets/3cb83bba-9d79-48b4-8067-b68cd933f5a3" />|

| 情感曲线 | 对比审稿 |
|----------|----------|
| <img width="2844" height="1542" alt="image" src="https://github.com/user-attachments/assets/bcfe9f0e-82c9-433f-8ba0-3f97e1958a48" />| <img width="2842" height="1544" alt="image" src="https://github.com/user-attachments/assets/9606060c-4eba-4e1a-a0ae-dd1f20e5e829" /> |

---

## ⚙️ 技术栈

- HTML5 / CSS3 / JavaScript（纯前端，无构建工具）
- [Tailwind CSS](https://tailwindcss.com/) — 样式系统
- [Alpine.js](https://alpinejs.dev/) — 响应式交互
- [Chart.js](https://www.chartjs.org/) — 情感曲线图表
- Google Fonts — Playfair Display + Inter + Noto Serif SC

---

## 📂 文件结构

```text
novelsoul-ai/
├── index.html      # 首页（品牌展示+Agent流程图）
├── diagnose.html   # 文本诊断（三维雷达图+扫描动画）
├── refine.html     # 多Agent协作润色（四通道面板+流式输出）
├── emotion.html    # 情感曲线图谱（双曲线对比+热力条）
├── review.html     # 对比审稿台（12处标注+悬浮批注）
└── README.md       # 项目说明
```

---

## 📜 License

MIT License

---
