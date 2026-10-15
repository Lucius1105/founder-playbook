# Founder Playbook · 创业者实战手册

**将 15 本商业书中的核心方法，整理成 AI 可参考和调用的结构化技能。**

每个书籍技能围绕一本书，提炼决策树、方法框架、案例和实用模板，帮助创业者把书里的方法用到客户访谈、产品定位、定价、销售和增长等具体问题中。

[English 原版说明](README.en.md) · [原始项目](https://github.com/getagentseal/founder-playbook) · [使用方法](#使用方法) · [来源与许可](#来源与许可)

> **中文版本说明**：本仓库是 [Lucius1105/founder-playbook](https://github.com/Lucius1105/founder-playbook)，Fork 自 **AgentSeal** 维护的 [getagentseal/founder-playbook](https://github.com/getagentseal/founder-playbook)。本仓库提供完整中文阅读版：仓库介绍与使用说明、16 个技能目录中的 78 份技能文档，以及 1 份实验记录均有中文版本。原路径默认显示中文；英文原稿保留为同目录的 `*.en.md`，首页英文原稿见 [README.en.md](README.en.md)。
>
> **翻译基线**：上游提交 [`e811e63`](https://github.com/getagentseal/founder-playbook/commit/e811e63be42c9b64a208707220b145451ad4b6c8)，核对日期为 2026 年 10 月 15 日。可查阅该版本的 [README 原文](https://github.com/getagentseal/founder-playbook/blob/e811e63be42c9b64a208707220b145451ad4b6c8/README.md)。

## 这是什么

Founder Playbook 是一个面向创业者的商业方法参考库，包含 **15 个书籍技能，以及 1 个帮助你选择方法的诊断技能 `diagnose`**。

原项目主要面向 Claude Code：安装后，Claude 可以根据问题选择相关技能。你也可以把文件作为参考资料提供给 ChatGPT、Gemini、Cursor 或其他大语言模型；具体加载方式取决于所用工具。

## 包含哪些内容

下表保留原书英文名和作者，便于追溯来源。技能标识和文件路径保持不变，点击进入中文正文；每份译文顶部提供英文对照和固定版本的上游原文链接。

| 技能 | 来源 | 适用场景 |
|------|------|----------|
| **[diagnose · 问题诊断](skills/diagnose/SKILL.md)** | **跨技能诊断入口，串联其余 15 个书籍技能** | **不知道从哪里开始；多个问题缠在一起；感觉“做什么都没用”** |
| [mom-test · 客户访谈](skills/mom-test/SKILL.md) | The Mom Test — Rob Fitzpatrick | 访谈客户；验证想法；避免诱导式提问 |
| [four-steps · 客户开发](skills/four-steps/SKILL.md) | The Four Steps to the Epiphany — Steve Blank | 寻找首批客户；客户开发；判断市场类型 |
| [lean-startup · 精益创业](skills/lean-startup/SKILL.md) | The Lean Startup — Eric Ries | 构建—衡量—学习循环；最小可行产品（MVP）；转型；创新核算 |
| [obviously-awesome · 产品定位](skills/obviously-awesome/SKILL.md) | Obviously Awesome — April Dunford | 产品定位；选择所属品类；理解竞争背景 |
| [crossing-the-chasm · 跨越鸿沟](skills/crossing-the-chasm/SKILL.md) | Crossing the Chasm — Geoffrey Moore | 技术采纳；选择滩头市场；进入主流市场并扩大规模 |
| [blue-ocean-strategy · 蓝海战略](skills/blue-ocean-strategy/SKILL.md) | Blue Ocean Strategy — W. Chan Kim & Renée Mauborgne | 创造新品类；开拓新的市场空间；摆脱同质化竞争 |
| [monetizing-innovation · 创新与定价](skills/monetizing-innovation/SKILL.md) | Monetizing Innovation — Madhavan Ramanujam & Georg Tacke | 定价策略；支付意愿；同步设计产品与价格 |
| [spin-selling · 顾问式销售](skills/spin-selling/SKILL.md) | SPIN Selling — Neil Rackham | B2B 销售；复杂交易；涉及多方决策者的销售 |
| [100m-offers · 产品与报价方案](skills/100m-offers/SKILL.md) | $100M Offers — Alex Hormozi | 设计和包装产品、服务与报价组合，提升购买吸引力 |
| [100m-leads · 获取销售线索](skills/100m-leads/SKILL.md) | $100M Leads — Alex Hormozi | 获取潜在客户；广告；主动触达与吸引客户的策略 |
| [money-models · 收入模式](skills/money-models/SKILL.md) | $100M Money Models — Alex Hormozi | 安排产品销售顺序；升级销售；降档销售；持续订阅；让客户收入覆盖获客成本 |
| [influence · 影响力](skills/influence/SKILL.md) | Influence — Robert Cialdini | 说服原则；谈判；识别并防范操纵 |
| [traction · 增长渠道](skills/traction/SKILL.md) | Traction — Gabriel Weinberg & Justin Mares | 增长渠道；靶心框架（Bullseye Framework）；客户获取 |
| [storybrand · 品牌表达](skills/storybrand/SKILL.md) | Building a StoryBrand — Donald Miller | 品牌信息；网站文案；邮件营销；SB7 品牌故事框架 |
| [made-to-stick · 让创意被记住](skills/made-to-stick/SKILL.md) | Made to Stick — Chip Heath & Dan Heath | 让信息更容易被记住；推介；演示；SUCCESs 框架 |

## 为什么做这个项目

商业书里有很多好框架，但它们往往散落在数百页故事中。读完、划过重点，过几个月却未必还记得该怎么用。原项目希望把值得反复使用的内容整理出来：

- **决策树**：判断“我的情况适合哪一种方法”。
- **方法框架**：具体模型、评分清单和逐步操作流程。
- **案例**：真实企业如何应用这些方法，以及应用失败的情形。
- **模板**：可以直接填写的工作表。
- **方法之间的关系**：不同书籍的框架在哪些地方互补，哪些地方存在冲突。

各书籍技能还讨论方法的适用范围：哪些观点有用、哪些内容已经过时，以及哪些情况不适合照搬。

## 使用方法

### 方法一：快速安装

在已安装 Node.js、可以使用 `npx` 的终端中运行：

```bash
npx skills add Lucius1105/founder-playbook
```

这是本中文仓库的地址，按安装器提示选择目标工具和技能即可。**安装命令默认读取仓库主分支；完整中文版合并到主分支后，才会通过该命令安装到。** 当前可先按下方预览分支命令手动安装。

如果希望安装 AgentSeal 维护的上游版本，可使用原命令：

```bash
npx skills add getagentseal/founder-playbook
```

### 方法二：手动安装到 Claude Code

以下命令适用于 macOS / Linux，需要已安装 Git。它会克隆本仓库，并把各技能链接到 `~/.claude/skills/`。已有同名文件、目录或链接会被跳过，避免覆盖你自己的技能。

```bash
# 克隆本仓库
git clone --branch docs/chinese-readme-20261015 https://github.com/Lucius1105/founder-playbook.git

# 准备 Claude Code 的个人技能目录
mkdir -p "$HOME/.claude/skills"

# 为每个技能建立链接，已有同名项则跳过
for skill in "$PWD"/founder-playbook/skills/*/SKILL.md; do
  [ -f "$skill" ] || continue
  dir="${skill%/SKILL.md}"
  name="${dir##*/}"
  target="$HOME/.claude/skills/$name"
  if [ -e "$target" ] || [ -L "$target" ]; then
    printf '已跳过已有技能：%s\n' "$name"
  else
    ln -s "$dir" "$target"
  fi
done
```

上面的命令指向本次完整中文预览分支。合并到主分支后，可以去掉 `--branch docs/chinese-readme-20261015`。上述命令应在同一个终端中依次运行；若克隆失败，先处理错误。链接依赖克隆目录，请保留该目录及路径。

安装后，可以直接用自然语言描述问题。Claude 会参考技能描述，按需要加载相关内容。例如：

- “我的创业项目到底哪里出了问题？” → `diagnose`：先诊断，再选择合适的技能。
- “我明天要访谈客户。” → `mom-test`。
- “我们是否应该转型？” → `lean-startup`。
- “我们应该选择哪个营销渠道？” → `traction`。
- “这个产品该怎么定价？” → `monetizing-innovation`。
- “我们的网站转化率很低。” → `storybrand`。
- “我的产品推介总是打动不了人。” → `made-to-stick`。

也可以直接调用已安装的技能，例如 `/lean-startup`、`/traction` 或 `/mom-test`。

### 方法三：在 ChatGPT、Gemini 或其他大语言模型中使用

1. 在上面的目录中选择与你的问题相关的技能。
2. 打开对应的 `SKILL.md`，把内容粘贴到对话中作为参考资料，并说明你的具体问题。
3. 需要更深入的内容时，再提供该技能目录下的相关配套文件，例如 `frameworks.md`、`cases.md` 或 `examples.md`；以目录中实际存在的文件为准。

文件开头的 YAML 区块主要记录名称、描述等元数据，使用时重点参考正文。技能正文和配套文件均有中文版本，可以直接用中文提问。文件中的技能 ID、可执行命令、URL、产品名称与框架缩写按需保留，避免影响调用或来源核对。

### 方法四：在 Cursor、Windsurf 或 Cline 中使用

将仓库放入项目的文档目录，或按对应工具的规则配置方式接入。提问时明确引用所需的 `SKILL.md`，让 AI 根据这些资料处理问题。自动引用和加载方式以各工具当前的配置为准。

## 技能文件如何组织

书籍技能通常采用“先看入口，再按需展开”的结构。以下是常见示例，具体文件以各目录为准：

```text
skill-name/
  SKILL.md        入口：决策树、关键框架和速查内容
  frameworks.md   详细框架：需要深入分析时阅读
  cases.md        书中企业案例：需要案例参考时阅读
  examples.md     模板、工作表和示例：具体应用时阅读
  integration.md  与其他技能的关联、互补和冲突
  *.en.md         对应文件的完整英文原稿
```

原 README 对这种分层加载的估计是：启动时，每个技能只读取约 100 tokens 的描述；触发后加载约 250—500 行的入口文件；配套文件按需加载。这些是原项目的概略说明，实际长度与上下文用量会随技能和工具而变化。

## 中文覆盖范围

| 内容 | 中文入口 | 覆盖情况 |
|------|----------|----------|
| 仓库介绍、安装及使用说明 | 本页 | 完整中文说明；保留英文 README |
| 15 个书籍技能＋1 个诊断技能 | 上方技能目录 | 78 份文档，涵盖入口、框架、案例、模板和方法配合 |
| 实验记录 | [真实创始人问题实验](experiments/real-founder-problems.md) | 1 份，含全部 10 个问题、对照表、评分及调整记录 |
| 插件界面 | `.codex-plugin/plugin.json` | 名称、介绍及示例提示词中文化 |
| 许可证阅读参考 | [MIT 许可证中文参考](LICENSE.zh-CN.md) | 附中文译文，正式 `LICENSE` 原样保留 |

英文原文逐文件保留，来源链接固定到翻译基线，不随上游后续修改而漂移。原文中发现的数字或逻辑冲突用“译注”单独说明；翻译不代表重新验证书中所有研究、平台规则或经营建议。实验评分来自上游记录，未作为本中文版的实际运行结果。原书名、作者名、书封图和必要技术标识保留原样。

## 推荐使用顺序

如果你正从创业想法走向规模化，可以参考以下顺序，也可以直接从眼前的问题切入：

| 顺序 | 技能 | 重点任务 |
|------|------|----------|
| 0 | `diagnose` | 不知道从哪里开始时，先定位问题 |
| 1 | `four-steps` | 找到客户，验证商业模式 |
| 2 | `lean-startup` | 通过构建—衡量—学习循环加快迭代 |
| 3 | `mom-test` | 学会不带偏客户的访谈方法 |
| 4 | `obviously-awesome` | 清晰地定位产品 |
| 5 | `storybrand` | 讲清价值，让客户愿意听 |
| 6 | `made-to-stick` | 让信息容易被记住，并促进行动 |
| 7 | `monetizing-innovation` | 同步设计产品与价格 |
| 8 | `100m-offers` | 包装有吸引力的产品、服务与报价方案 |
| 9 | `money-models` | 安排销售组合与顺序，让客户收入覆盖获客成本 |
| 10 | `spin-selling` | 推进 B2B 交易成交 |
| 11 | `crossing-the-chasm` | 从早期采用者走向主流客户 |
| 12 | `blue-ocean-strategy` | 面临同质化时，寻找新的市场空间 |
| 13 | `traction` | 用靶心框架系统筛选增长渠道 |
| 14 | `100m-leads` | 在选定渠道中落实获客动作 |
| 15 | `influence` | 在全过程中理解和运用说服原则 |

## 这些技能有什么特点

- **明确适用边界**：指出书中哪些观点可能有误、哪些已经过时、哪些情境不适用。
- **呈现框架之间的冲突**：例如 Blue Ocean Strategy 与 Obviously Awesome 对细分市场的不同主张，在相关 `integration.md` 中说明并讨论如何处理。
- **补充当代适用性说明**：提醒读者，20 世纪 90 年代和 21 世纪初的框架，在 2025 年之后的产品驱动增长（PLG）、AI 原生产品、隐私法规等背景下，可能需要调整。
- **便于实际应用**：内容包含决策树、评分标准和可填写模板，帮助把阅读转化为具体行动。

## 使用示例

向 AI 描述：

> “我做了一个 AI 工具，和 30 个人聊过，他们都说喜欢，但没有一个人付费。问题出在哪里？”

原项目用这个例子说明，多种方法可以如何配合分析：

- **Mom Test**：对方说“喜欢”可能只是客气，需要改用了解真实行为和需求的问题。
- **Four Steps**：可能跳过了客户验证，可用早期核心客户（earlyvangelist）的需求层级来评估客户。
- **Lean Startup**：价值假设可能尚未验证，需要用创新核算方法衡量真实需求。
- **StoryBrand**：检查网站是否只在介绍自己，而没有讲清客户的问题，再用品牌故事脚本（BrandScript）改进表达。

这是原 README 中的应用示意，展示分析思路，不代表 AI 每次都会自动调用全部技能，也不代表这些推测已经得到客户事实验证。

## 原著书目

<table>
  <tr>
    <td align="center"><img src="covers/four-steps-to-the-epiphany.jpg" width="120"><br><sub>The Four Steps to the Epiphany<br>Steve Blank</sub></td>
    <td align="center"><img src="covers/the-lean-startup.jpg" width="120"><br><sub>The Lean Startup<br>Eric Ries</sub></td>
    <td align="center"><img src="covers/the-mom-test.jpg" width="120"><br><sub>The Mom Test<br>Rob Fitzpatrick</sub></td>
    <td align="center"><img src="covers/obviously-awesome.jpeg" width="120"><br><sub>Obviously Awesome<br>April Dunford</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="covers/monetizing-innovation.jpg" width="120"><br><sub>Monetizing Innovation<br>Ramanujam & Tacke</sub></td>
    <td align="center"><img src="covers/100m-offers.jpeg" width="120"><br><sub>$100M Offers<br>Alex Hormozi</sub></td>
    <td align="center"><img src="covers/spin-selling.jpg" width="120"><br><sub>SPIN Selling<br>Neil Rackham</sub></td>
    <td align="center"><img src="covers/crossing-the-chasm.jpg" width="120"><br><sub>Crossing the Chasm<br>Geoffrey Moore</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="covers/blue-ocean-strategy.jpg" width="120"><br><sub>Blue Ocean Strategy<br>Kim & Mauborgne</sub></td>
    <td align="center"><img src="covers/traction.jpg" width="120"><br><sub>Traction<br>Weinberg & Mares</sub></td>
    <td align="center"><img src="covers/influence.webp" width="120"><br><sub>Influence<br>Robert Cialdini</sub></td>
    <td align="center"><img src="covers/100m-leads.jpg" width="120"><br><sub>$100M Leads<br>Alex Hormozi</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="covers/building-a-storybrand.jpg" width="120"><br><sub>Building a StoryBrand<br>Donald Miller</sub></td>
    <td align="center"><img src="covers/made-to-stick.jpg" width="120"><br><sub>Made to Stick<br>Chip & Dan Heath</sub></td>
    <td align="center"><img src="covers/100m-money-models.jpg" width="120"><br><sub>$100M Money Models<br>Alex Hormozi</sub></td>
    <td></td>
  </tr>
</table>


## 支持原作者

这些技能是辅助学习与批判性讨论的资料，用来帮助你应用书中的方法。完整的背景、案例和作者论述仍需要回到原著阅读。如果某个技能对你有帮助，欢迎购买原书、支持作者。

下表保留上游 README 提供的原书购买链接。

| 原书 | 作者 | 购买链接 |
|------|--------|--------|
| The Four Steps to the Epiphany | Steve Blank | [Amazon](https://www.amazon.com/Four-Steps-Epiphany-Steve-Blank/dp/0989200507) |
| The Lean Startup | Eric Ries | [Amazon](https://www.amazon.com/Lean-Startup-Entrepreneurs-Continuous-Innovation/dp/0307887898) |
| The Mom Test | Rob Fitzpatrick | [Amazon](https://www.amazon.com/Mom-Test-customers-business-everyone/dp/1492180742) |
| Obviously Awesome | April Dunford | [Amazon](https://www.amazon.com/Obviously-Awesome-Product-Positioning-Customers/dp/1999023005) |
| Crossing the Chasm | Geoffrey Moore | [Amazon](https://www.amazon.com/Crossing-Chasm-3rd-Disruptive-Mainstream/dp/0062292986) |
| Blue Ocean Strategy | W. Chan Kim & Renee Mauborgne | [Amazon](https://www.amazon.com/Blue-Ocean-Strategy-Expanded-Uncontested/dp/1625274491) |
| Monetizing Innovation | Madhavan Ramanujam & Georg Tacke | [Amazon](https://www.amazon.com/Monetizing-Innovation-Companies-Design-Product/dp/1119240867) |
| SPIN Selling | Neil Rackham | [Amazon](https://www.amazon.com/SPIN-Selling-Neil-Rackham/dp/0070511136) |
| $100M Offers | Alex Hormozi | [Amazon](https://www.amazon.com/100M-Offers-People-Refuse-ebook/dp/B099QVG1H8) |
| $100M Leads | Alex Hormozi | [Amazon](https://www.amazon.com/100M-Leads-Strangers-Want-ebook/dp/B0CFDR4VT8) |
| $100M Money Models | Alex Hormozi | [Amazon](https://www.amazon.com/100M-Money-Models-Make-Acquisition-com/dp/1963349156) |
| Influence | Robert Cialdini | [Amazon](https://www.amazon.com/Influence-New-Expanded-Psychology-Persuasion/dp/0062937650) |
| Traction | Gabriel Weinberg & Justin Mares | [Amazon](https://www.amazon.com/Traction-Startup-Achieve-Explosive-Customer/dp/1591848369) |
| Building a StoryBrand | Donald Miller | [Amazon](https://www.amazon.com/Building-StoryBrand-Clarify-Message-Customers/dp/0718033329) |
| Made to Stick | Chip Heath & Dan Heath | [Amazon](https://www.amazon.com/Made-Stick-Ideas-Survive-Others/dp/1400064287) |

## 来源与许可

- **原始开源项目与整理者**：[Founder Playbook](https://github.com/getagentseal/founder-playbook)，由 [AgentSeal](https://github.com/getagentseal) 维护。
- **本中文整理仓库**：[Lucius1105/founder-playbook](https://github.com/Lucius1105/founder-playbook)。仓库文档根据上游对应文件翻译整理，中文翻译由 AI 辅助完成；每份技能及实验译文都注明原出处。
- **本轮改动范围**：完整中文化 README、78 份技能文档、1 份实验记录和插件的用户可见说明；保留对应英文原稿，另附许可证中文参考。安装示例与插件仓库地址指向本中文分支；保留上游作者署名与正式许可证。
- **书籍来源**：上述 15 本书及其作者。AgentSeal 是开源项目整理者，书籍中的原创思想与内容应追溯到各自原作者。本中文整理版不是书籍全文翻译。
- **开源许可证**：[MIT License](LICENSE)。保留原版权声明：`Copyright (c) 2026 AgentSeal`。书籍与封面等第三方材料的权利仍归相应权利人；仓库的 MIT 许可不表示这些原著与图片也被重新授予 MIT 许可。

如上游更新，后续翻译应继续对照固定版本，保留英文原稿，并区分上游内容与译者补充。
