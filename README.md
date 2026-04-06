# Senior Game Designer

---

A senior game design skill package. It's a rigorous thinking framework that pushes back — enumerating all possibilities to make you reconsider, probing constraints to expose blind spots, asking "why not this way" so you can't coast on intuition.

> This Skill helps you push the four boundaries to their limits — enumerating constraints, recursing through layers, descending layer by layer, letting boundaries reveal themselves. It can't guarantee good design, but it systematically reduces bad design: skipping layers, missing constraints, logical inconsistencies, unanticipated risks — all exposed by the structured process.

---

## 1. Methodology

### 1.1 Definition of Design

**Good design = pushing four boundaries to their limits**

| Boundary | Description |
|----------|-------------|
| Financial | Spend every yuan where it counts most |
| Effort | Maximize ROI on human and player time |
| Environment | Leverage the era's historical moment. A design meaningful in this era may be meaningless in another; good design catches the node that pushes society forward |
| Cognitive | Maximize information delivery and emotional reach without overloading |

The design process is finding where these four boundaries are, then pushing past them.

---

**Constraints are tools, not the goal.**

Constraints help you locate the boundaries — but the boundaries are the destination. Finding the boundaries and pushing past them is the goal of design.

---

#### 1.1.1 Types of Constraints

| Type | Examples |
|------|----------|
| Limit-type | Budget cap, technically impossible, understaffed, platform limits |
| Goal-type | DAU target, day-1 retention >50%, pay rate >10% |
| Feeling-type | Players must feel accomplished, surprised, see growth |
| Emotion-type | Players must laugh, feel urgency, feel suspense |
| Value-type | Fair trades, meaningful progression, effort rewarded |
| Pacing-type | Under 5 min per session, tension and release, ups and downs |
| Problem-type | How players will misunderstand, where they get stuck, where they'll be bored |

Problems encountered are one aspect of constraints — not all. **Constraints also include what you must preserve, what you must create, what feeling you must give players.**

---

#### 1.1.2 Layers of Constraints

**Constraints have layers.**

Layer 1 has Layer 1 constraints. When entering Layer 2, you discover constraints unique to Layer 2. When entering Layer 3, you discover constraints unique to Layer 3. Unknown constraints unfold layer by layer as you descend — they are unknown at Layer 1, become known only when you reach Layer 2.

What this means:

- **Known constraints** are the starting point at the current layer — what boundaries exist, what must be preserved. E.g.: at Layer 1, it's "mobile pacing 5-7 min". At Layer 2, it becomes "information visibility design is the core execution-level difficulty". At Layer 3, it becomes "the specific form of settlement feedback"
- **Unknown constraints** are where design value lies — boundaries only discoverable at the next layer. Unknown constraints at Layer N become known constraints at Layer N+1. Design descends layer by layer; each layer down, constraints get more concrete, the solution gets closer to executable
- **Unknown constraints don't appear out of thin air** — they emerge as you descend through layers. The deeper you go, the more concrete the constraints become, the closer you get to an executable solution

---

### 1.2 Good Design vs Bad Design

**Bad design:** stops before pushing any boundary to its limit. Digs a bit at Layer 1, jumps to Layer 2, digs a bit, jumps to Layer 3. Every boundary falls short — budget overruns a little, cognitive load overflows a little, misses the era's moment. The result is mediocre on all four boundaries.

---

**Good design:** enumerates every layer until no new constraints emerge, pushes every boundary to its limit. Budget spent fully but not over, player cognition just saturated, caught the era's historical node, effort and return perfectly balanced. When constraints are exhausted, boundaries reveal themselves — the solution didn't emerge from imagination, it was pushed into existence.

---

### 1.3 Top-Down Recursive Methodology

Start with the top-level goal, expand downward layer by layer. Each layer's questions can only be answered within that layer — lower-layer problems cannot answer upper-layer questions.

Top-Down is not just a slogan — it has three specific operating mechanisms:

**Constraints have layers.** Layer 1 has Layer 1 constraints. When entering Layer 2, you discover Layer 2's new constraints. When entering Layer 3, you discover Layer 3's new ones. Unknown constraints unfold layer by layer as you descend — they don't appear out of thin air. Unknown constraints at each layer become known constraints at the next layer.

**Top-Down is a recursive methodology.** Starting from the top layer, every layer does the same thing: enumerate (breadth) → filter by constraints → recurse to the next layer. Unknown constraints at Layer N become known constraints at Layer N+1. Raw material from enumeration at Layer N, after being cut by constraints, enters Layer N+1 to repeat the process. Until all layers are exhausted and the solution takes shape naturally.

**Breadth ensures maximum possibility.** Enumerate all possible variants at the current layer without judging right or wrong, without pre-excluding anything. More possibilities mean more room to choose when entering the next layer.

**Constraints provide value judgment baseline.** After enumeration, use current-layer constraints to filter — does this variant align with the layer's goals? Does it preserve what must be kept? Discard what doesn't fit, keep what does.

---

#### 1.3.1 Recursive Loop

```
Enumerate at current layer (breadth)
    → Filter by constraints
    → Enter next layer to discover new constraints
    → Enumerate at next layer
...until all layers are exhausted
```

---

> **If the top layer is wrong, the harder you work on lower layers, the worse it gets.**
> **If the top layer is right, lower layers finally matter.**

---

### 1.4 Sign & Feedback Theory

Sign is an **elegant guiding methodology** used in the polish phase. It's not a top-level design tool, nor a system design tool — it's about refining rule communication and perception guidance.

Sign is a method that lets players **understand rules through exploration, not memorization.** Zelda: burn grass → see updraft → discover wind mechanic without a tutorial. That's Sign — the world speaks for itself.

**Sign's core value:** reduces cognitive load, lets players understand a new world and its rules without tutorials.

- Sign makes rule learning an **exploration process** instead of a **memorization process**
- Sign makes the environment itself the **best tutorial**
- Sign means design **doesn't need pop-ups and text** to communicate rules

Sign tells players **what the rules are**. Feedback tells players **what the results are**. They can be separate or chained — last-second Feedback can become next-second Sign.

---

#### 1.4.1 Two Types of Sign

- **Implicit** (environmental hints, roads/coins/world fragments) gives discovery
- **Explicit** (QTE/tutorial/status highlight) gives rhythm

Both essential.

**Sign (elegant):** Signposts, coins, towers, world fragments, updraft visualization, ultimate highlight, health bar turning red

**Feedback (confirming):** Kill animations, reward animations, number changes, result broadcasts

---

### 1.5 Neurotransmitter-Driven Theory

Player fun is essentially two neurotransmitter-driven learning loops:

| Neurotransmitter | Function | Covers |
|-----------------|---------|--------|
| Dopamine | Expectation/motivation | Easy Fun (curiosity), new discovery |
| Endorphin | Accomplishment + social adhesion | Hard Fun, Serious Fun, People Fun |

**Dopamine** drives exploration. Unknown/expectation → exploration → dopamine release → motivation reinforcement → continue. Dopamine covers Easy Fun (curiosity satisfaction) and joy of discovering new content.

**Endorphin** drives consolidation, with two functions: **pain relief + social adhesion**. Pain relief produces accomplishment, covering Hard Fun (overcoming difficulty) and Serious Fun (collecting satisfaction); social adhesion produces belonging, covering People Fun (joy of being with others).

**A healthy game has both.** Dopamine only → motivated to explore but nothing to show for it and no sense of belonging, churn fast. Endorphin only → accomplishment but no drive to explore, eventually bored.

---

<br>

## 2. Core Principles

- **Design is top-down** — from top-level to features, layer by layer
- **Constraint first, then breadth, then depth** — no skipping
- **Can players learn something new** — the only test for whether design is fun
- **Output documents, not discussion** — write .md files immediately
- **Mermaid diagrams are mandatory** — no pure text loop descriptions

**Decision matrix:** Replaces the "fast/cheap/good" triangle in the AI era. The only standard: can players learn something new? Four dimensions: Fun / Differentiation / Lifecycle / Top-level alignment (veto).

**Top-Down iterative check:** Theme consistency runs through all phases, not just once at the top. Every phase must answer: which top-level experience does this design strengthen?

**Core judgment standard:** Can players learn something new? Learning can be new patterns ("this combo works better") or new content (new characters/scenes).

---

<br>

## 3. Five-Layer System

| Layer | Question Answered | Output |
|-------|-----------------|--------|
| Layer 1: Top-level | What is the game? What experience does it give players? | Top-level doc + 3 required diagrams |
| Layer 2: System architecture | Which major systems are needed? Which depends on which? | System diagram + design intent |
| Layer 3: Internal system | How does the system work? Where are decision points? | System design doc |
| Layer 4: Feature design | What does this feature do? What are the trade-offs? | Feature design doc |
| Layer 5: Polish | Are numbers right? Is pacing smooth? | Tuning suggestions |

---

<br>

## 4. Four-Phase Workflow

Every subsystem must complete all 4 phases — no skipping.

```
Phase 1 → Constraint     What can this design do? Where are the boundaries?
Phase 2 → Breadth       Enumerate all variants, identify subsystems
Phase 3 → Depth        Judge core driver, filter variants
Phase 4 → Design doc   Complete design doc, ready for development
```

---

<br>

## 5. Three Required Diagrams (Layer 1)

1. **Core loop diagram** — Mermaid flowchart, verb flow, the smallest closed loop players want to repeat
2. **Full loop diagram** — Mermaid flowchart, core loop's connections to peripheral systems
3. **Resource flow diagram** — Mermaid flowchart TD, all resource production and consumption loops

---

<br>

## 6. How This Differs from Other Game Design Skills

Most game design skills on the market are **template-fillers** — give you a format, ask you to fill it in. This produces documents that look standardized but doesn't guarantee the design itself is right.

| Dimension | Other Skills | This Skill |
|-----------|-------------|------------|
| Method | Fill templates | Constraint → Breadth → Depth |
| Standard | "Is the format right?" | "Can players learn something new?" |
| Output | Documents | Executable decisions + documents |
| Decision basis | Subjective experience | Decision matrix (Fun / Diff / Lifecycle / Alignment) |
| Loop expression | Text description | Mermaid diagrams (required) |
| Consistency check | None | Top-Down across all phases |
| Risk handling | Avoided | Core risks + worst-case responses |

**One-line summary:** Not a format to fill in, but a thinking framework that forces you to be clear — what experience does this design solve, and why would players find it fun.

---

<br>

## 7. File Structure

```
game-designer/
├── SKILL.md              # Core skill file
├── README.md             # This file
├── references/           # Reference docs (19)
│   ├── Methodology
│   ├── Player Experience
│   ├── Genre Mechanics
│   └── UI & Interaction
└── examples/             # Templates + Examples (6)
```

References are from *100 Game Design Principles* (Wendy Despain) and other general game design methodologies, filtered and reorganized through a top-level design lens.

---

<br>

## 8. Quick Start

1. Receive a design request
2. Confirm which layer it belongs to
3. Decide which phases to go through
4. Copy the corresponding template from `examples/`
5. Fill it → next phase → fill → next phase
6. Complete all phases → update archive index

---

<br>

## 9. Author & License

**Author:** TIGERMKIII

**License:** MIT License — Free to use, modify, and distribute with attribution.

---

<br>

---

# 高级游戏策划

---

高级游戏策划技能包。它是一个严谨的、能反驳你的思维框架——会穷举所有可能让你重新审视，会追问约束让你暴露盲区，会说"为什么不是这样"让你无法用直觉过关。

> 这个 Skill 帮你把四个边界推到极限——穷举约束、递归层级、逐层下降，让边界自己显现。它不能保证做出好设计，但它能系统地减少差设计的数量：跳层、遗漏约束、逻辑不自洽、没预判风险，这些问题在结构化的流程里无处可藏。

---

## 1. 原创方法论

### 1.1 设计的定义

**好设计 = 在四个边界上推到极限**

| 边界 | 说明 |
|------|------|
| 财力边界 | 不浪费每一分钱，预算的每一份投入都物尽其用 |
| 精力边界 | 人力和玩家时间的投入产出比最高 |
| 环境边界 | 充分利用人类社会的时代节点。某个设计在这个时代有意义，放在其他时代可能毫无意义；好的设计刚好踩中了推动社会前进的那个节点 |
| 认知边界 | 在不超载的前提下最大化信息的传达和情感的触达 |

设计的过程，就是找到这四个边界在哪里，然后推过去。

---

**约束是工具，不是目的。**

约束帮你定位边界在哪里——但边界才是终点。找到边界、推到极限，才是设计的目标。

---

#### 1.1.1 约束的类型

| 类型 | 举例 |
|------|------|
| 限制型约束 | 预算上限、技术做不到、人手不足、平台限制 |
| 目标型约束 | DAU 要达到多少、次留要超过 50%、付费率要 10% |
| 感受型约束 | 玩家要有成就感、要有惊喜感、要有成长可见 |
| 情绪型约束 | 玩家要笑、要有紧迫感、要有悬念 |
| 价值型约束 | 公平交易、积累有意义、努力有回报 |
| 节奏型约束 | 单次不超过 5 分钟、要有张有弛、要有起伏 |
| 问题型约束 | 玩家会误解什么、会卡在哪里、会无聊 |

遇到的问题是约束的一方面，不是全部。**约束还包括你必须保留的东西、必须创造的东西、必须让玩家感受到的东西。**

---

#### 1.1.2 约束的层级

**约束是有层级的。**

第一层有第一层的约束，进入第二层时发现第二层才有的约束，进入第三层时发现第三层才有的约束。未知约束随层级下降逐层展开——它在第一层时是未知的，进入第二层时才变成已知。

这句话的意思：

- **已知约束**是当前层的起点——当前层有哪些边界，哪些东西是必须保留的。比如：第一层时是"手游节奏 5-7 分钟"，进入第二层时变成"信息可见性设计是执行级核心难点"，进入第三层时变成"结算反馈的具体形式"
- **未知约束**是设计的价值所在——进入下一层才会发现的边界。第一层的未知约束就是第二层的已知约束。设计的过程是逐层下降，每降一层，约束就具体一分，方案就成型一分
- **未知约束不是凭空出现的**，它藏在层级下降的过程中。越往下走，约束越具体，越接近可执行的方案

---

### 1.2 好设计与差的设计

**差的设计：** 在某个边界还没推到底时就停了。第一层挖了一部分，跳进第二层，第二层又挖了一部分，跳进第三层。结果每个边界都差一口气——预算超了一点，认知超载了一点，环境没利用完。最后出来的东西在四个边界上都是半吊子。

---

**好的设计：** 每一层都穷举到没有新约束为止，每一个边界都推到极限。预算用完但不多花，玩家认知刚好饱和，环境空间充分利用，精力投入产出比最高。约束被穷举完的那一刻，边界自然显现——方案不是想出来的，是推出来的。

---

### 1.3 Top-Down 递归方法论

先有顶层目标，逐层向下展开。每一层的问题只能在当前层回答，不能用下层的问题来回答。

Top-Down 不是一句口号，它有三个具体的操作机制：

**约束有层级。** 第一层有第一层的约束，进入第二层时会发现第二层的新约束，进入第三层时又发现第三层的新约束。未知约束是随层级下降逐层展开的，不是凭空出现的。每一层的未知约束，就是下一层的已知约束。

**Top-Down 是递归方法论。** 从顶层开始，每一层做同样的事：穷举（广度）→ 约束筛选 → 递归进入下一层。每一层的未知约束，是下一层的已知约束；每一层穷举的原料，经过约束裁刀后，进入下一层继续这个过程。直到所有层都挖完，方案自然成型。

**广度保证最大的可能性。** 在当前层穷举所有可能的变体，不预判对错，不提前排除。可能性越多，进入下一层时的选择空间越大。

**约束提供价值观判断基准。** 穷举完之后，用当前层的约束来筛选——这个变体是否符合该层的目标？是否符合必须保留的东西？不符合的丢弃，符合的保留。

---

#### 1.3.1 递归循环

```
当前层穷举（广度）
    → 约束筛选
    → 进入下一层发现新约束
    → 下一层穷举
...直到所有层都挖完
```

---

> **顶层错了，下层越努力越糟糕。**
> **顶层对了，下层才有意义。**

---

### 1.4 Sign 与 Feedback 论

Sign 是一个**优雅的指导性方法论**，用在 polish 阶段。它不是顶层设计工具，也不是系统设计工具——是 polish 时用来打磨规则传达和感知引导的精致度。

Sign 是让玩家**通过探索理解规则，而不是通过记忆理解规则**的方法。塞尔达火烧草地出现上升气流——玩家不需要教程，不需要弹窗，直接在环境里自己发现"风是这个世界的机制之一"。这就是 Sign：世界用自己的语言和玩家说话。

**Sign 的核心价值：** 降低认知门槛，让玩家在不依赖教程的情况下理解全新的世界和规则。

- Sign 让规则学习变成**探索过程**而不是**记忆过程**
- Sign 让环境本身成为**最好的教程**
- Sign 让设计**不需要堆弹窗和文字**来完成规则传达

Sign 告诉玩家**规则是什么**。Feedback 告诉玩家**结果是什么**。两者可以独立存在，也可以连续成链——上一秒的 Feedback 结果，可以成为下一秒的 Sign（玩家根据结果预判下一次行动）。

---

#### 1.4.1 Sign 分两种

- **隐式**（环境暗示，路标/金币/碎片世界观）让玩家有发现感
- **显式**（QTE/教程/状态高亮）让玩家有节奏感

两者缺一不可。

**Sign（优雅的）：** 路标、金币、高塔、碎片世界观、上升气流可视化、大招高亮、血条变红

**Feedback（确认的）：** 击杀动画、获得奖励动画、数值变化、结果播报

---

### 1.5 递质驱动论

玩家的乐趣本质上是两种神经递质驱动的学习循环：

| 递质 | 功能 | 覆盖的 Fun |
|------|------|-----------|
| 多巴胺 | 期待/动机 | Easy Fun（好奇心）、新内容发现 |
| 内啡肽 | 成就感 + 社交粘性 | Hard Fun、Serious Fun、People Fun |

**多巴胺**驱动探索。未知/期待 → 探索行为 → 多巴胺释放 → 动机强化 → 继续探索。多巴胺覆盖 Easy Fun（好奇心满足）和发现新内容的惊喜。

**内啡肽**驱动巩固，有两个功能：**镇痛 + 社交粘性**。镇痛产生成就感，覆盖 Hard Fun（克服困难）和 Serious Fun（收集满足）；社交粘性产生归属感，覆盖 People Fun（与人在一起的快乐）。

**健康的游戏两者都有。** 只有多巴胺 → 有探索动力但没有积累感和归属感，流失快。只有内啡肽 → 有成就感但没有探索动力，最终无聊。

---

## 2. 核心原则

- **设计是自上而下的过程** — 从顶层到功能，逐层展开
- **先约束，再广度，后深度** — 不能跳步
- **玩家是否有新东西可学** — 是判断设计是否有趣的唯一标准
- **输出文档，不是对话** — 拿到需求立即写 MD 文件
- **Mermaid 图是必须产出** — 循环图禁止纯文字描述

**决策矩阵：** AI 时代替代"快/好/便宜"三角。判断标准只有一条：玩家是否有新东西可以学习。四个维度：有趣度 / 差异化 / 生命周期 / 顶层支持（一票否决）。

**Top-Down 迭代检查：** 主题一致性贯穿所有 Phase，不是只在顶层做一次。每个 Phase 都要回答：这个设计强化了哪个顶层体验？

**核心判断标准：** 玩家是否有新东西可以学习。学习可以是新规律（"原来这个组合效果更好"）或新内容（新角色/新场景）。

---

<br>

## 3. 五层设计体系

| 层级 | 回答的问题 | 输出 |
|------|-----------|------|
| 第一层：顶层设计 | 游戏是什么？给玩家什么体验？ | 顶层设计文档 + 三个必须图 |
| 第二层：系统架构 | 需要哪些大系统？谁是谁的基础？ | 系统架构图 + 设计目的 |
| 第三层：系统内部 | 系统怎么运作？决策点在哪？ | 系统设计文档 |
| 第四层：功能设计 | 这个功能做什么？代价和收益是什么？ | 功能设计文档 |
| 第五层：polish | 数值合适吗？节奏流畅吗？ | 调整建议 |

---

<br>

## 4. 四 Phase 工作流

每个子系统必须完整走完 4 个 Phase，不能跳步。

```
Phase 1 → 约束探索     这个设计能做什么？边界在哪？
Phase 2 → 广度探索     穷举所有变体，找出子系统
Phase 3 → 深度收束     判断核心驱动力，筛选变体
Phase 4 → 执行文档     完整设计文档，可直接用于开发
```

---

<br>

## 5. 必须产出的三个图（第一层）

1. **核心循环图** — Mermaid flowchart，动词流，玩家愿意反复做的最小闭环
2. **完整循环图** — Mermaid flowchart，核心循环与外围系统的连接关系
3. **数值与道具流向图** — Mermaid flowchart TD，所有资源的产出和消耗闭环

---

<br>

## 6. 与其他游戏策划 Skill 的区别

市面上的游戏策划 Skill 大多是**模板填充器**——给你一堆格式，问你填什么。这只能产出看起来规范的文档，不能保证设计本身是对的。

| 维度 | 其他 Skill | 本 Skill |
|------|-----------|----------|
| 工作方式 | 填模板 | 先约束探索，再穷举变体，再深度收束 |
| 判断标准 | "格式对不对" | "玩家能学到新东西吗" |
| 产出 | 文档 | 可执行的决策 + 文档 |
| 决策依据 | 主观经验 | 决策矩阵（有趣度/差异化/生命周期/顶层支持）|
| 循环表达 | 文字描述 | Mermaid 图（强制要求）|
| 一致性检查 | 无 | Top-Down 迭代贯穿所有 Phase |
| 风险处理 | 避而不谈 | 核心风险 + 最坏情况应对 |

**一句话总结：** 不是给你一个格式让你填，而是用一套思考框架逼你想清楚——这个设计解决的是什么体验，玩家凭什么觉得它有趣。

---

<br>

## 7. 文件结构

```
game-designer/
├── SKILL.md              # 核心技能文件
├── README.md             # 本文件
├── references/           # 参考文档（19个）
│   ├── 方法论
│   ├── 玩家体验
│   ├── 品类机制
│   └── UI交互
└── examples/             # 模板 + 示例（6个）
```

references 来自《游戏设计的100个原理》（Wendy Despain）和其他通用游戏设计方法论，经过顶层设计视角筛选和重组。

---

<br>

## 8. 快速开始

1. 拿到一个设计需求
2. 确认属于哪个层级
3. 确定需要走完哪几个 Phase
4. 复制 `examples/` 中对应的模板文件
5. 填完 → 下一个 Phase → 填完 → 下一个 Phase
6. 完整走完 → 更新归档索引

---

<br>

## 9. 作者与协议

**作者：** TIGERMKIII

**协议：** MIT License — 可自由使用、修改和分发，引用请注明来源。
