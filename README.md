<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 044 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 044

### 把源图决定性的形态压进一片克制纯金

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D7AE42?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-183A3E?style=flat-square)](#)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> 薄层纯金 · 正面平面 · 源图深底 · 锤纹压痕 · 安静秩序

源图决定性剪影以真实薄层黄金直接铺在深色平面：金箔、锻金、压印金属或浅层铸金，并保留柔光、锤纹、褶皱、翘边与少量断裂。

## 为什么需要这套 Skill

这套风格依赖每一张源图，不是可替换内容的装饰预设。它遵循这条重构链：

```text
锁定决定性剪影与结构 → 保留三个线索 → 把体积压成一幅薄层纯金材质图形 → 选择与源图隐性关联的深纯底色 → 以锤纹、压印、褶皱、翘边与金箔断裂分布柔和金属反射 → 正面无畸变摄影 → 让文字成为压印或低对比材质细节
```

如果换成无关照片后，辨识度、构造、位置、材质、颜色、留白与文案都不发生实质变化，结果就不属于这套 Panel。

## 视觉契约

- 从轮廓、比例、姿态、方向、动作、开口、结构转折或关系中保留至少三个源图专属线索。
- 坚持薄层平面材质逻辑：金箔、锻金片、压印金属或浅层铸金铺在底面，不得成为立体雕塑或厚重金块。
- 呈现高纯度黄金从哑光到柔光的细腻光泽、温和反射、小锤纹、压印、边缘起伏、褶皱、浅浮雕与选择性金箔断裂。
- 使用完全正面、平视镜头，以及与源图关联的深、净、克制底面和大面积安静留白，无任何透视畸变。
- 只让一个纯金主体成为焦点；反射服从真实材质起伏，不得镜面刺光、俗黄或奢侈品广告戏剧感。

完整审美约束与拒绝项写在 Skill 和生产提示词中；它们保留原始提示词的审美动机，但不会把历史 3:4 画布变成隐藏默认值。 [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-044-prompt.en.md)

## 样张 · 即将补充

`assets/examples/` 只会放入项目作者确认过的本风格成品；未确认前不使用其他风格作为占位。

## 四种可组合输出模式

可以用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 张 PNG：三种普通模式各一张，外加四张壁纸。

| 模式 | 未指定尺寸 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 `W×2H` | 上方完整源图＋下方变化设计，严格 50/50 |
| `left-right` | 源图自适应 `2W×H` | 左侧完整源图＋右侧变化设计，严格 50/50 |
| `design-only` | 源图自适应 `W×H` | 只显示变化设计，不出现原照片 |
| `wallpaper-pack` | 设备分别标注尺寸 | 手机、iPad、电脑、儿童手表四张独立 PNG |

壁纸可选连贯或独立。连贯套装先批准一张定调图，所有设备都共同参考原图与这同一锚点，绝不裁切或串联衍生图；独立套装每张只参考原图。

## 文案与语言

正式生成前确认自动文案、准确自定义文案或无文字；语言跟随目标受众而不是命令语言，用户给出的准确文案逐字保留。

本项目的文案规则： 使用一个极短主体、动作、情绪或隐喻标题及仅必要的微文案；把目标语言文字做成细致金属压印、浅浮雕、边缘标记或属于同一平面的低对比排印。

## 几何、位图与可信边界

普通模式未指定尺寸时按源图自适应；双联严格 50/50，全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务，绝不泄露私密生成路线信息。

已配置的位图桥只输出脱敏状态，绝不暴露服务方、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图都不能代替最终位图作品。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-044.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-044" ~/.codex/skills/xxd-panel-044
```

Claude Code 用户可把同一文件夹链接到 `~/.claude/skills/xxd-panel-044`. 安装后请重启 Agent 会话。

```text
$xxd-panel-044
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完整规格: [Skill 工作流](SKILL.md) · [原始风格档案](references/044-source.md) · [英文生产提示词](references/xxd-panel-044-prompt.en.md) · [中文生产提示词](references/xxd-panel-044-prompt.zh-CN.md)

## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 支持与会员

### 深度咨询 · 299 元／小时

一对一深入咨询 Skills 的使用与工作流，通过微信联系小小东预约。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### 小小东 Skills 用户交流群 · 99 元

一次付费加入 Skills 用户交流群，用于工作流分享和用户间讨论；不包含按小时计费的一对一咨询。

### 知识星球＋成员提示词库 · 699 元／年

知识星球和成员提示词库是一份会员费用：从任一入口开通后，通过微信联系小小东获取另一边的权益。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>黄金保住形态时才有意义，而不是用来表演昂贵。</strong></div>

---

<div align="center">

## ☕ 支持这个开源项目

算力赞助请使用小小东自己的微信或支付宝赞赏码；赞助完全自愿，不改变开源项目的访问权限。


<table><tr>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD WeChat reward" width="180"></a><br><strong>WeChat</strong></td>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD Alipay reward" width="180"></a><br><strong>Alipay</strong></td>
</tr></table>

</div>
</div>
