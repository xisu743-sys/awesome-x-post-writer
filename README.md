# awesome-x-post-writer

一个用来写 X post 和 reply 的 Skill。

## 覆盖范围

| 场景 | 内容 |
|---|---|
| 原创发帖 | 8 个切入角度：数字冲击、反直觉、宣言、hot take、对比、工程细节、推论、punchline |
| 回复他人推文 | 先判断原帖关系、语境和回复任务，再选择表达方式 |
| 个人号 voice | 以账号真实历史为准，匹配大小写、标点、emoji、长度和正式程度 |
| ego lite 官方号 | 5 种场景模式、品牌事实红线、写作流程，以及带语境说明的真实正例 |

新版不再把“短”理解为所有场景都必须短。核心原则是：**没有多余的话，但该介绍产品或解释技术时要说完整。**

## 文件

```text
SKILL.md
└── 通用路由、写作方法和检查规则

references/ego-lite-official.md
└── ego lite 官方账号 persona、场景模式和决策流程

references/ego-lite-examples.md
└── 已发布正例及其适用语境
```

处理 ego lite 官方账号文案时，agent 必须读取两个 reference 文件。其他账号只需使用 `SKILL.md`，避免加载无关品牌上下文。

## 安装

把下面这段直接发给 Claude Code 或 Codex：

```text
帮我安装这个 skill：
git clone https://github.com/xisu743-sys/awesome-x-post-writer.git ~/.claude/skills/x-writer
装完确认 ~/.claude/skills/x-writer/SKILL.md 存在，然后告诉我装好了。
```

也可以手动安装：

```bash
git clone https://github.com/xisu743-sys/awesome-x-post-writer.git ~/.claude/skills/x-writer
```

## 使用

- “帮我写条推文，内容是……”
- “这条 tweet 我想回复一下”
- “给 ego lite 官方号写个视频发布文案”
- “用 ego lite 官方账号回复这个 roadmap 问题”
- “write a reply to this product question”
