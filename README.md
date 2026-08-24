<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 050 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 050

### 让每张照片长成专属的空气蓝旅行视觉

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D5898C?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-6FA4B7?style=flat-square)](#)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 定制旅行场景 · 空气蓝 · 极简平涂矢量 · 编辑留白 · 一图一身份

把源图中最有辨识度的主体与叙事关系，转化为一张专为它设计的高级旅行视觉：一个主焦点、2–4 个有依据的环境线索、安静留白和轻盈蓝调，而不是只替换城市名的通用模板。

## 为什么需要这套 Skill

```text
锁定主体、姿态与叙事关系 → 保留三个专属线索 → 选定一个主视觉焦点 → 从源图提炼 2–4 个环境证据 → 按主体气质重组场景而不是套模板 → 用空气蓝平涂矢量语言统一 → 留出安静呼吸 → 让标题与 tagline 成为场景身份的一部分
```

如果换成无关照片后，主体辨识、辅助线索、空间秩序、配色关系和文案都不发生实质变化，结果就不属于这套 Panel。

## 视觉契约

- 至少保留三个源图专属线索，不把主体压缩成通用图标。
- 只建立一个主焦点，搭配 2–4 个有源图依据的环境线索；人物如有必要，仅保留 3–6 个小尺度角色。
- 场景类型由源图决定，不堆无关地标，不套城市名或明信片模板。
- 使用日系文具感、精品贴纸插画与现代旅行品牌气质：简洁几何、柔和轮廓、统一线重、平涂色块、克制细节和充足留白。
- 配色以浅粉蓝、雾蓝、天空蓝或空气感冷蓝为主，以象牙白、奶油白、浅米色、柔和灰绿与建筑中性色平衡；灰粉只作少量点缀。
- 拒绝写实、塑料 CG、渐变、纹理、厚重阴影、拥挤背景、地标拼贴和重复版式。

完整规格见 [SKILL.md](SKILL.md) 与 [生产提示词](references/xxd-panel-050-prompt.zh-CN.md)。它们保留原始审美动机，但不会把历史 3:4 画布变成隐藏默认值。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091461184516227185) · 2026 年 8 月 23 日<br>
> GPT2 × 矢量插画 × 旅行 × 简洁 × 美学提示词 × VOL.050

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 050 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 050 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 050 样张 3"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091461184516227185">查看原推文与完整提示词 →</a></p>

这些样张用于展示 050 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种可组合输出模式

可用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 个独立 PNG。模式确定后，Skill 会在生图前继续询问整张最终成品的画幅：`3:4` 原提示词画幅、明确跟随原图、常用比例，或自定义比例／准确像素。不会再静默套用源图尺寸。

| 模式 | 画幅逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在上，050 设计在下，约 50/50 |
| `left-right` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在左，050 设计在右，约 50/50 |
| `design-only` | 用户确认的整张成品画幅 | 050 设计铺满画布，不显示原照片 |
| `wallpaper-pack` | 逐设备确认 | 手机、iPad、电脑、儿童手表四张独立 PNG |

双联默认把原图作为高保真垫图／编辑参考，用一套完整提示词直接生成一张整体成品，让摄影、设计、色彩、光线、文字与含义自然呼应。只有完整画布针对性重试仍失败、用户要求原片逐像素不变、当前通道无法实现目标画幅，或需要无创像素校准时，才启用确定性拼合兜底。

壁纸可选连贯或独立。连贯套装先批准一张 iPad 定调图，另外三张分别参考原图＋同一定调图重新构图；独立套装的四张都只参考原图。两者都不会裁切其他设备成品或串联衍生图。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 勾选式选择与快捷参数

当运行环境提供真正的交互控件时，Skill 会优先使用卡片式选择：成品模式和普通成品尺寸均可多选，文字方式与壁纸关系为单选。尺寸提供自动适配、跟随原图、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5 和自定义比例／像素。没有交互控件时，会自动改用清楚的多行编号菜单，不显示无法点击的假复选框。

所有设置也可以作为变量直接跟在调用指令后：

```text
/xxd-panel-050 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text auto --locale ja-JP
```

可使用 `--mode`、可重复或逗号分隔的 `--size`、`--text auto|custom|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size` 和 `--out`。参数齐全时跳过全部问询并直接生成；参数不完整时只补问缺失项。不同比例会分别重新构图，四端壁纸仍是独立设备分支，不与普通尺寸机械相乘。

## 生图模型优先级

GPT Image 2 是默认首选，并继续执行本项目现有的高保真垫图、生成前确认整张画幅、双联一次生成完整画布、脚本仅作条件式兜底等逻辑。

当当前工具或已配置兼容通道确实可用，并能满足原图保真、整张成品比例、目标语言文字和连贯壁纸多图参考等要求时，也支持 Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）或其他兼容位图模型。备用模型只替换生成通道，不得改变模式、画幅、文案、语言、壁纸关系和完整画布优先策略。

如果没有合适的生图通道，Skill 会请用户启用生图工具或提供 API Key。用户主动提供的凭据可以用于当前任务，但不得在回复或日志中回显、展示或泄露；未经用户明确要求，不会长期保存凭据或修改供应商、账户、计费及全局路由配置。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-050.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-050" ~/.codex/skills/xxd-panel-050
```

Claude Code 用户可把同一文件夹链接到 `~/.claude/skills/xxd-panel-050`。安装后请重启 Agent 会话。

```text
$xxd-panel-050
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完整规格：[Skill 工作流](SKILL.md) · [原始风格档案](references/050-source.md) · [英文生产提示词](references/xxd-panel-050-prompt.en.md) · [中文生产提示词](references/xxd-panel-050-prompt.zh-CN.md)

## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。

## 支持与会员

- 深度咨询：299 元／小时，通过[微信](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)预约。
- 小小东 Skills 用户交流群：99 元，一次付费入群；不含一对一咨询。
- 知识星球＋成员提示词库：699 元／年，一次年费同时开通两项权益。若从[知识星球](https://wx.zsxq.com/group/15554814142882)开通，请微信联系小小东领取[成员提示词库](https://vip.xiaoxiaodong.ai/)兑换码；若在成员提示词库自助开通，请微信联系小小东邀请进入知识星球。

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>不是替换一个地名，而是让这张照片拥有自己的旅行身份。</strong></div>

---

<div align="center">

## ☕ 支持这个开源项目

算力赞助请使用小小东自己的微信或支付宝赞赏码；赞助完全自愿，不改变开源项目的访问权限。

<table><tr><td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD WeChat reward" width="180"></a><br><strong>WeChat</strong></td><td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD Alipay reward" width="180"></a><br><strong>Alipay</strong></td></tr></table>

</div>
