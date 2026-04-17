<!--
 * @Author: 岳泽以 2980008080@qq.com
 * @Date: 2026-04-16 23:00:38
 * @LastEditors: 岳泽以 2980008080@qq.com
 * @LastEditTime: 2026-04-16 23:01:50
 * @FilePath: \pages.com\design.md
 * @Description: 
-->
# 设计系统 — 视觉宪法

16个设计系统，每个都是自足的视觉宪法。AI代理可以阅读任何一个文件，理解的不只是系统*长什么样*，而是*为什么*——每种颜色选择、每个圆角、每道阴影背后的哲学。这些不是变量清单。它们是设计师对开发者的口述。

> 实际上是17个。OpenTiny加入了——它的主色是#191919，几乎是黑色。这是唯一一个用黑按钮做品牌的系统。

---

## 光谱一览

| 系统 | 主色 | 哲学 |
|---|---|---|
| [Ant Design](design-systems/ant-design.md) | #1677FF | "企业规模下的笃定从容" |
| [Element Plus](design-systems/element-plus.md) | #409EFF | "Vue生态中的沉静自信" |
| [Arco Design](design-systems/arco-design.md) | #165DFF | "克制的丰盈——深色模式作为一等公民" |
| [Semi Design](design-systems/semi-design.md) | #6B53F7 | "内容优先的效率配创意紫" |
| [TDesign](design-systems/tdesign.md) | #0052D9 | "包容的专业——欢迎每个人的平台" |
| [NutUI](design-systems/nutui.md) | #FA2C19 | "零售紧迫感——商业红说'立即行动'" |
| [Vant](design-systems/vant.md) | #1988FA | "移动速度下的轻量商业" |
| [Naive UI](design-systems/naive-ui.md) | #2080F0 / #63E2B7 | "彻底的可定制性——暗色薄荷即身份" |
| [DevUI](design-systems/devui.md) | #5E7CE0 | "沉静天空——12小时监控轮班的低饱和蓝" |
| [HiUI](design-systems/hiui.md) | #FF6900 | "亲和的科技——物联网规模的温暖" |
| [Varlet](design-systems/varlet.md) | #2979FF | "移动Web的Material忠实实现" |
| [Material Design 3](design-systems/material-design-3.md) | #6750A4 | "表达性的个性化——动态色彩、色调表面" |
| [Fluent Design 2](design-systems/fluent-design-2.md) | #0078D4 | "温暖的专业——亚克力、揭示高亮和包容交互" |
| [Carbon](design-systems/carbon-design-system.md) | #0F62FE | "系统的严谨——尖角、无装饰、三种深色模式" |
| [Lightning](design-systems/lightning-design-system.md) | #0176D3 | "CRM规模下的企业信任" |
| [Apple HIG](design-systems/apple-hig.md) | #007AFF | "对内容的敬畏即清晰" |
| [OpenTiny](design-systems/opentiny.md) | #191919 | "沉默的权威——黑按钮即品牌" |

---

## 主色速览

```
Ant Design     ██ #1677FF  "企业蓝——确定性的颜色"
Element Plus   ██ #409EFF  "沉静蓝——不呐喊的自信"
Arco Design    ██ #165DFF  "深邃蓝——不令人疲劳的丰盈"
Semi Design    ██ #6B53F7  "创意紫——非企业、非商业"
TDesign        ██ #0052D9  "信任蓝——欢迎所有人的平台"
NutUI          ██ #FA2C19  "商业红——立即行动、立即购买"
Vant           ██ #1988FA  "信任蓝——移动速度下的安全交易"
Naive UI       ██ #2080F0  "开发者蓝" / ██ #63E2B7 "薄荷——建造者构建的工具"
DevUI          ██ #5E7CE0  "沉静天空——长轮班的稳定蓝"
HiUI           ██ #FF6900  "温暖橙——有脉搏的科技"
Varlet         ██ #2979FF  "Material蓝——熟悉的Android温暖"
Material 3     ██ #6750A4  "表达紫——你的颜色、你的身份"
Fluent 2       ██ #0078D4  "专业蓝——温暖、包容、可信赖"
Carbon         ██ #0F62FE  "严谨蓝——系统的、不废话"
Lightning      ██ #0176D3  "企业蓝——CRM规模的信任"
Apple HIG      ██ #007AFF  "系统蓝——内容优先，Chrome退让"
OpenTiny       ██ #191919  "沉默权威——黑按钮即品牌"
```

---

## 设计DNA对比

每个系统下了不同的赌注。以下是让每个系统独特的关键架构决策。

| 系统 | 按钮圆角 | 卡片圆角 | 正文字号 | 触摸目标 | 标志性特质 |
|---|---|---|---|---|---|
| Ant Design | 6px | 8px | 14px | 32px | 确定性布局——8px网格配24列精度 |
| Element Plus | 4px | 4px | 14px | 32px | 低语表面——边框优于阴影 |
| Arco Design | 4px | 8px | 14px | 32px | 深色模式作为一等公民配10步色阶 |
| Semi Design | 3px | 8px | 14px | 32px | DSM桥梁——Figma令牌直接流入代码 |
| TDesign | 6px | 8px | 14px | 32px | 8px卡片圆角作为"平台"信号——亲和而非企业 |
| NutUI | 4px | 8px | 14px | 44px | 商业红——促成交的紧迫感 |
| Vant | 4px | 8px | 14px | 44px | 仅限移动端——没有桌面断点，375px优先 |
| Naive UI | 4px | 8px | 14px | 34px | CSS-in-JS令牌——不用var()，用useThemeVars() |
| DevUI | 4px | 8px | 14px | 32px | 低饱和沉静——为12小时监控轮班设计 |
| HiUI | 8px | 12px | 14px | 44px | 12px卡片圆角=温暖——手机、电视、自助终端通用 |
| Varlet | 4px | 4px | 14px | 48px | Material 2忠实——涟漪效果、高度语义 |
| Material 3 | 20dp（药丸） | 12dp | 14px | 48dp | 动态色彩——系统成为用户的身份 |
| Fluent 2 | 6px | 8px | 14px | 44px | 亚克力材质+揭示高亮+双环焦点 |
| Carbon | 0px（尖角） | 0px（尖角） | 14px | 44px | 零圆角=零装饰——三种深色主题强度 |
| Lightning | 4px | 4px | 14px | 44px | 36px紧凑表格行——CRM数据密度 |
| Apple HIG | 10pt（连续） | 10pt（连续） | 17pt | 44pt | 连续曲线+SF Pro光学尺寸+通透材质 |
| OpenTiny | 6px | 8px | 14px | 32px | 黑按钮#191919——彩色只做语义，不做表达 |

---


## 如何使用这些文件

每个文件都是独立的视觉宪法。把其中一个交给AI代理，说：

> "按照这个设计系统为我构建一个[产品类型]。"

代理会理解哲学、颜色角色、组件解剖、高度语义和布局规则——不只是hex值。它会知道*为什么*一个按钮是6px圆角而非4px，*为什么*一道阴影使用暖灰而非纯黑，*为什么*深色模式不只是反转色而是一个精心调校的平行世界。
