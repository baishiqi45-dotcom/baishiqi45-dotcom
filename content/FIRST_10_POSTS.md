# First 10 Public Content Drafts

Each draft is written for publication after a final human pass. Do not attach
private screenshots, prompt packages, scripts, or production assets.

## 1. AI 短剧不是提示词问题，是控制边问题

Platform:

```text
即刻 / 小红书
```

Hook:

```text
很多 AI 短剧看起来散，不是因为提示词不够长，而是因为没有控制边。
```

Body:

AI 生成最容易骗过人的地方是：单张图、单个镜头都还行，一剪到一起就散。角色脸变了、空间变了、动作接不上、情绪断了，最后大家只会说“再生成一版”。

我现在更关注的不是怎么写更华丽的 prompt，而是先问五个问题：

1. 角色什么必须不变？
2. 空间什么不能漂？
3. 道具状态要不要继承？
4. 动作因果怎么接？
5. 情绪是延续、反转，还是被打断？

这些问题就是控制边。没有控制边，生成越多，返工越多。

Visual suggestion:

```text
一张五锁表格：角色 / 空间 / 道具 / 动作 / 情绪
```

CTA:

```text
下次我拆一个“字段齐全但不好看”的 AI 短剧样例。
```

Boundary:

```text
Use synthetic or self-owned examples only.
```

## 2. 为什么“字段齐全”的 AI 短剧还是不好看

Platform:

```text
小红书 / B站短视频
```

Hook:

```text
字段齐全只能证明它像生产表，不代表它像戏。
```

Body:

AI 短剧生产里有一个误区：把人物、场景、镜头、提示词都填满，就以为片子会成立。可观众看的不是表格，观众看的是“这一秒我为什么要继续看”。

我会把问题拆成三层：

- 信息层：观众知道了什么？
- 行动层：人物做了什么？
- 交易层：这 5 秒让观众获得了什么情绪回报？

如果只有信息，没有行动，就像简介。  
如果只有行动，没有情绪交易，就像素材。  
如果只有情绪词，没有可见动作，就像提示词作文。

Visual suggestion:

```text
三层图：信息 / 行动 / 情绪交易
```

CTA:

```text
想看我把一个失败镜头拆成这三层，可以留言一个 AI 短剧片段类型。
```

Boundary:

```text
Do not use copyrighted clips without permission.
```

## 3. 北影导演怎么把镜头判断翻译成 agent 任务

Platform:

```text
LinkedIn / 即刻
```

Hook:

```text
导演说“这里要压迫感”，agent 不知道该改什么。
```

Body:

人的导演语言经常是感性的：压迫、疏离、暧昧、危险。但 agent 需要的是可执行字段。

所以我会把一句导演判断翻译成：

- performance：演员怎么做；
- blocking：人在空间里怎么动；
- camera：观众被迫看什么；
- transition：这一镜怎么把能量交给下一镜；
- asset role：哪个参考图是绑定的，哪个只是气氛；
- review rule：什么情况算失败；
- retake target：失败时只改哪个字段。

这不是把导演变成工程师，而是把导演判断变成可交接的生产语言。

Visual suggestion:

```text
DirectorShotIR field card
```

CTA:

```text
方法卡已整理在 GitHub profile 的 DirectorShotIR field card。
```

Boundary:

```text
Use synthetic examples, not private project prompts.
```

## 4. 五条连续性锁：让 AI 生成别再串脸、串空间、串动作

Platform:

```text
小红书 / 即刻
```

Hook:

```text
AI 视频连续性不是玄学，至少先锁住这五件事。
```

Body:

我现在会先锁五件事：

1. 角色锁：这个人靠什么被认出来？
2. 空间锁：这一镜必须继承哪个空间事实？
3. 道具锁：物件状态有没有改变？
4. 动作锁：上一秒动作怎么接到下一秒？
5. 情绪锁：人物心理是延续还是反转？

每次返修不要说“更一致一点”，而要说：

```text
失败字段：空间锁
具体问题：门的位置和上一镜不一致
返修范围：只改空间关系，不改角色服装和镜头情绪
```

Visual suggestion:

```text
一张返修卡模板
```

CTA:

```text
返修卡已整理成 AI video continuity locks 模板。
```

Boundary:

```text
Template only; no private image references.
```

## 5. Project Clinic：非工程师做 AI 产品前先问这 6 个问题

Platform:

```text
LinkedIn / 即刻
```

Hook:

```text
非工程师做 AI 产品，第一步不是找 agent 写代码。
```

Body:

先问 6 个问题：

1. 这个需求的原始意图是什么？
2. 哪些资料是真的 source，哪些只是想法？
3. 现在缺哪一类资料？
4. 应该先研究、先原型、先设计，还是先停？
5. 谁拥有最终验收权？
6. 这轮做完，什么经验可以写回下次复用？

这就是 Project Clinic 的起点。它不是拖慢速度，而是防止一上来就把 agent 派到错误战场。

Visual suggestion:

```text
Project Clinic startup packet diagram
```

CTA:

```text
公开版 Project Clinic startup packet 已放在 GitHub profile。
```

Boundary:

```text
Do not present this as engineering completion.
```

## 6. 从剧本到抽卡包：AI 影像生产总控链

Platform:

```text
B站 / YouTube / LinkedIn
```

Hook:

```text
AI 影像生产不是从 prompt 开始，是从“什么可以被派发”开始。
```

Body:

我把后剧本阶段拆成一条链：

```text
剧本意图
  -> 视觉参考角色
  -> image evidence
  -> shot/package instruction
  -> QA boundary
  -> retake note
  -> operator handoff
```

关键不是多生成，而是每个包都知道：

- 这包要证明什么；
- 哪些参考是绑定的；
- 哪些失败必须拦住；
- 操作员能改什么；
- 结果回填后怎么判断下一步。

Visual suggestion:

```text
Animated control-chain diagram
```

CTA:

```text
完整 synthetic case 已放在 GitHub profile，不含私有剧本和提示词。
```

Boundary:

```text
Do not imply provider submission or final video acceptance.
```

## 7. 别让 sidecar 变成真理机器：外部模型只应该当顾问

Platform:

```text
X / LinkedIn / 即刻
```

Hook:

```text
多问一个模型，不等于多一份真理。
```

Body:

我用外部模型 sidecar 时，只把它当顾问：

- 它不能直接读完整私有项目；
- 它只能看窄证据包；
- 它的输出是风险或替代意见；
- Codex/主控必须本地验证；
- 最终判断仍然属于项目 owner。

坏模式是“另一个模型也这么说，所以是真的”。  
好模式是“另一个模型指出了一个风险，我回到证据里检查它”。

Visual suggestion:

```text
Bad pattern vs good pattern diagram
```

CTA:

```text
这也是我把 sidecar repo 降级成 reference slice 的原因。
```

Boundary:

```text
Do not market sidecar as an autonomous truth engine.
```

## 8. 看过不等于学会：我的视频知识五层消化协议

Platform:

```text
小红书 / 即刻
```

Hook:

```text
看 100 个 AI 影像教程，不等于你的片子会变好。
```

Body:

我更关心视频知识怎么变成可迁移的方法。五层消化：

1. Capture：记录来源和片段；
2. Structure：拆成动作、镜头、情绪、节奏；
3. Grounding：标出证据和不确定；
4. Transfer：转成自己的方法卡；
5. Retention：进入下一次项目的检查表。

重点是：不要搬运别人的内容，要抽象出自己的创作判断。

Visual suggestion:

```text
Five-layer digestion ladder
```

CTA:

```text
空白方法卡模板已放在 GitHub profile 的 templates 目录。
```

Boundary:

```text
No screenshots, subtitles, or long excerpts from closed sources.
```

## 9. 生成后怎么审：AI 视频 admission gate

Platform:

```text
LinkedIn / 即刻
```

Hook:

```text
AI 视频生成完，不代表它可以进剪辑。
```

Body:

我会用五级 admission ladder：

1. Source evidence：原始 artifact 在哪里；
2. Static evidence：帧、contact sheet、manifest；
3. Playback evidence：有没有人看过关键片段；
4. Relation evidence：它和前后镜头是什么关系；
5. Owner seal：谁有权说它 accepted。

没有 owner seal，就不要说 final。  
没有 playback evidence，就不要说“我理解了视频”。  
没有 relation evidence，就不要说“连续性没问题”。

Visual suggestion:

```text
Admission ladder card
```

CTA:

```text
这套 gate 已整理成 Video Admission Ladder 模板。
```

Boundary:

```text
No final/accepted claims without public owner evidence.
```

## 10. 我为什么不再用 GitHub star 当核心目标

Platform:

```text
即刻 / LinkedIn / X
```

Hook:

```text
GitHub star 是发现机制，不是我的商业目标。
```

Body:

我之前也容易被“开源项目要有人 star”带偏。但复盘后发现，我真正有价值的不是几个小工具，而是这些工具背后的控制方法：

- AI 影像怎么从剧本进入可派发生产包；
- 非工程师怎么判断 AI 产品第一步；
- 生成后怎么审；
- 失败后怎么返修；
- 什么东西不能假装已经验证。

所以我把旧 repo 降级成 building blocks。它们还在，但不再是主角。主角是方法、案例和能帮真实项目少走弯路的判断力。

Visual suggestion:

```text
Before: repo list / After: method-control loop
```

CTA:

```text
现在可以从 GitHub profile 的 methods、cases、templates 入口直接看方法。
```

Boundary:

```text
Do not disparage open source; reposition it as proof appendix.
```
