<!--
 * @Author: 岳泽以 2980008080@qq.com
 * @Date: 2026-04-16
 * @Description: 项目说明文档
-->
<div align="center">

# Univ Design

**消除代码的 AI 味，注入你的风格**

17 份设计系统视觉宪法——让 AI Agent 写出有灵魂的代码

[探索风格](#17种风格分类) · [使用教程](#使用方式) · [下载全部](#下载)

</div>

---

## 这是什么

AI 生成的界面总有一种统一的"AI味"——千篇一律的紫色渐变、模板化的 8px 圆角、深色模式就是 `invert()`。

**问题不在 AI，在于你只给了它 hex 值，没有给它哲学。**

Univ Design 收录了 17 个主流设计系统的**视觉宪法**——每份文档不是冰冷的变量清单，而是设计师对开发者的口述。每种颜色有角色，每条规则有理由，每个圆角值背后都有"为什么"。

把其中一份交给 AI Agent，它就知道的不只是"长什么样"，而是"为什么长这样"。

---

## 目录结构

```
univ-design/
├── index.html                 # 在线展示网站
├── design.md                  # 总索引：17个系统的一览表与DNA对比
├── README.md                  # 项目说明（本文件）
└── design-systems/            # 设计系统文档目录
    ├── ant-design.md          # 企业规模下的笃定从容
    ├── element-plus.md        # Vue生态中的沉静自信
    ├── arco-design.md         # 克制的丰盈——深色模式一等公民
    ├── semi-design.md         # 内容优先的效率配创意紫
    ├── tdesign.md             # 包容的专业——欢迎每个人的平台
    ├── nutui.md               # 零售紧迫感——商业红
    ├── vant.md                # 移动速度下的轻量商业
    ├── naive-ui.md            # 彻底的可定制性——暗色薄荷
    ├── devui.md               # 沉静天空——低饱和监控蓝
    ├── hiui.md                # 亲和的科技——物联网温暖橙
    ├── varlet.md              # 移动Web的Material忠实实现
    ├── material-design-3.md   # 表达性的个性化——动态色彩
    ├── fluent-design-2.md     # 温暖的专业——亚克力与揭示
    ├── carbon-design-system.md # 系统的严谨——尖角零装饰
    ├── lightning-design-system.md # CRM规模下的企业信任
    └── apple-hig.md           # 对内容的敬畏即清晰
    └── opentiny.md              # 沉默的权威——黑按钮即品牌
```

---

## 17种风格分类

### 企业后台

| 系统 | 主色 | 核心差异 |
|------|------|----------|
| Ant Design | `#1677FF` | 6px按钮圆角，24列网格，三字重节奏 |
| Element Plus | `#409EFF` | 4px统一圆角，边框优于阴影，双字重（400/700） |
| Arco Design | `#165DFF` | 10步算法色阶，深色模式一等公民 |
| Semi Design | `#6B53F7` | 创意紫，DSM双向同步，3px工具感圆角 |
| DevUI | `#5E7CE0` | 低饱和"沉静蓝"，12小时监控轮班优化 |
| Carbon | `#0F62FE` | 0px尖角，8px严格网格，三种深色主题（g10/g90/g100） |
| OpenTiny | `#191919` | 黑按钮品牌，彩色仅语义角色，4px原子间距 |

### 移动商业

| 系统 | 主色 | 核心差异 |
|------|------|----------|
| NutUI | `#FA2C19` | 商业红="机会"，44px触摸，375px优先 |
| Vant | `#1988FA` | 信任蓝，仅移动端，14px/1.43行高 |
| Varlet | `#2979FF` | Material 2忠实，涟漪效果，48dp触摸目标 |

### 消费 / IoT

| 系统 | 主色 | 核心差异 |
|------|------|----------|
| HiUI | `#FF6900` | 温暖橙，12px卡片圆角，适配电视/自助终端 |

### 开发者工具

| 系统 | 主色 | 核心差异 |
|------|------|----------|
| Naive UI | `#2080F0` / `#63E2B7` | CSS-in-JS令牌，暗色薄荷标志，2px按钮增量 |

### 平台生态

| 系统 | 主色 | 核心差异 |
|------|------|----------|
| TDesign | `#0052D9` | 8px"平台"圆角，3px宽焦点环，跨10+平台 |
| Lightning | `#0176D3` | 36px紧凑表格行，CRM数据密度 |

### 平台规范

| 系统 | 主色 | 核心差异 |
|------|------|----------|
| Material Design 3 | `#6750A4` | 20dp药丸按钮，动态色彩种子，色调高度 |
| Fluent Design 2 | `#0078D4` | 亚克力材质，揭示高亮，双环焦点 |
| Apple HIG | `#007AFF` | 连续曲线，SF Pro光学尺寸，高度即亮度 |

---

## 文档规范

每份设计系统文档遵循统一的 **9 大章节**结构：

| 章节 | 内容 |
|------|------|
| 视觉主题与氛围 | 设计哲学、核心原则、整体调性 |
| 色彩体系与角色 | 语义色表（角色/令牌/色值/原因）+ 深色模式 |
| 排版规则 | 字体选择、字阶表（级别/字号/字重/原因） |
| 组件样式 | 按钮、卡片、输入框等核心组件的精确规格 |
| 布局原则 | 基础单位、间距比例、网格、圆角等级 |
| 深度与高度 | 阴影层级表（级别/用途/阴影值/原因） |
| 宜与忌 | 设计系统的强制约束 |
| 响应式行为 | 断点表与适配策略 |
| 代理提示指南 | 快速调色板 + 即用提示词 |

---

## 使用方式

### 核心用法：放入项目，告诉代理读取

1. 将选中的设计系统 `.md` 文件放入你的项目目录
2. 告诉你的编码代理读取此文件，根据其中的设计规范构建匹配的用户界面

```
请读取项目中的 ant-design.md，然后根据其中的设计规范构建匹配的用户界面
```

代理读取文档后，会理解哲学、颜色角色、组件解剖和布局规则——不只是 hex 值。它会知道为什么按钮是 6px 圆角而非 4px，为什么阴影使用暖灰而非纯黑，为什么深色模式不是反转色而是精心调校的平行世界。

### 给开发者用

- **选型参考**：阅读 `design.md` 总索引中的"设计DNA对比"表，快速找到适合项目的设计系统
- **开发规范**：将对应系统的文档作为开发约束，确保团队实现一致
- **主题定制**：参照色彩令牌表和深色模式章节，系统性覆盖设计变量

### 选型建议

| 你在做什么 | 推荐系统 | 理由 |
|-----------|---------|------|
| 企业后台管理系统 | Ant Design / Element Plus | 成熟生态，丰富组件，社区支持强 |
| 需要深色模式的后台 | Arco Design | 深色模式一等公民，10步算法色阶 |
| Vue 3 后台项目 | Element Plus / Arco Design | Vue 生态深度适配 |
| 电商小程序 | NutUI | 商业红促成交，移动优先 |
| 移动端 H5 | Vant | 轻量，375px 优先，仅移动端 |
| 开发者工具 | Naive UI / Semi Design | 高可定制性，开发者向 |
| 跨平台应用 | TDesign | 跨 10+ 平台一致性 |
| IoT / 多端适配 | HiUI | 温暖橙，适配电视/自助终端 |
| Material 风格 | Varlet / Material Design 3 | Material 忠实实现 |
| Microsoft 风格 | Fluent Design 2 | 亚克力材质，Windows 生态 |
| Apple 风格 | Apple HIG | 连续曲线，SF Pro，通透材质 |
| 企业级严格系统 | Carbon | 0px 尖角，零装饰，三种深色模式 |
| 极简无主见后台 | OpenTiny | 黑按钮品牌，彩色仅语义，4px原子间距 |
| Salesforce 生态 | Lightning | CRM 数据密度，36px 紧凑行 |

---

## 下载

### 直接下载

点击仓库中的 `design-systems/` 目录，逐个下载 `.md` 文件。

### Clone 仓库

```bash
git clone https://github.com/你的用户名/univ-design.git
```

### 在线预览

打开 `index.html` 即可在浏览器中查看交互式展示网站。

---

## 维护说明

- 新增设计系统时，在 `design-systems/` 下创建对应的 `.md` 文件，遵循 9 大章节结构
- 同步更新 `design.md` 总索引中的三个表格（光谱一览、主色速览、DNA对比）
- 同步更新 `README.md` 中的分类表格和选型建议
- 同步更新 `index.html` 中的 `systems` 数据数组
- 保持中文撰写风格：每种颜色有角色，每条规则有理由，保留设计哲学的灵魂语气
- 令牌名、hex 色值、CSS 属性值保持英文/原样，不翻译

---

## License

MIT License — 自由使用、修改和分发。

---

## 官方链接

| 设计系统 | 官方网站 |
|---------|---------|
| Ant Design | https://ant.design |
| Element Plus | https://element-plus.org |
| Arco Design | https://arco.design |
| Semi Design | https://semi.design |
| TDesign | https://tdesign.tencent.com |
| NutUI | https://nutui.jd.com |
| Vant | https://vant-ui.github.io/vant |
| Naive UI | https://www.naiveui.com |
| DevUI | https://vue-devui.github.io |
| HiUI | https://hiui.hoperun.com |
| Varlet | https://varlet.gitee.io/varlet-ui |
| Material Design 3 | https://m3.material.io |
| Fluent Design 2 | https://fluent2.microsoft.design |
| Carbon Design System | https://carbondesignsystem.com |
| Lightning Design System | https://www.lightningdesignsystem.com |
| Apple HIG | https://developer.apple.com/design |
| OpenTiny | https://opentiny.design |

---

## 鸣谢

感谢以上所有设计系统的团队——是你们的哲学、规范和开源精神让这个项目成为可能。Univ Design 是对这些优秀设计系统的整理与致敬，而非替代。

本项目中所有设计系统的知识产权归原团队所有。

---

## 声明

本项目由 AI 辅助完成，包括文档撰写、代码生成和站点构建。

---

<div align="center">

**Univ Design** · 消除 AI 味，写你的风格

</div>
