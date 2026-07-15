# awesome-x-post-writer

一个 Claude Code Skill，教 AI（也教人）按我们验证过的方法写 X（Twitter）发帖和回复文案。

写 X 内容最大的问题不是没话说，是写出来一股 AI 味：emoji 满天飞、句句工整、结尾总结升华、开头 "Great point"。这份 skill 把我们从多个高互动账号实测提炼出来的语气规则、结构模板、思考步骤和自查清单整理成一份文件，写之前照着想，写完照着查。

## 覆盖范围

| 场景 | 内容 |
|------|------|
| 原创发帖（post） | 8 个切入角度模板（数字冲击、反直觉、宣言、hot take、对比、工程细节、推论、punchline），每个角度写明何时不适用；6 步写作流程 |
| 回复他人推文（reply） | 关系矩阵：先判断原帖作者是谁、什么调性，再决定用哪种 voice；认真回之前先过 5 个自检问题 |
| 个人号 voice | 通用方法论，不锁定任何具体账号。先翻自己最近 20-30 条已发帖子定位自己的风格，再套通用规则 |
| ego lite 官方号 voice | 具体规则：禁第一人称、产品名可自报、痛点场景开场加 agent 接管的结构，附实际发布过的范本文案 |

另外还有两套通用防线：

- **语气红线**：8 类禁用的 AI 味短语（每类附为什么是 AI 味）、6 种结构性 AI 味（不是用词问题，是骨架问题）、全文禁 emoji / hashtag / em-dash
- **英文小毛病自查**：动词及物性、时态、平台地道用语（X 的输入框叫 compose box 不叫 input frame）这类翻译腔陷阱

## 安装

把下面这段直接复制发给你的 agent（Claude Code / Codex 都行），它会自己装好：

```
帮我安装这个 Claude Code skill：
git clone https://github.com/braxtonROSE4/awesome-x-post-writer.git ~/.claude/skills/x-writer
装完确认 ~/.claude/skills/x-writer/SKILL.md 存在，然后告诉我装好了。
```

装完重启 Claude Code 会话即可生效。

也可以自己手动装，就一条命令：

```bash
git clone https://github.com/braxtonROSE4/awesome-x-post-writer.git ~/.claude/skills/x-writer
```

## 使用

在 Claude Code 里直接说需求就会触发，比如：

- "帮我写条推文，内容是……"
- "这条 tweet 我想回复一下，帮我写"
- "给 ego lite 官方号写个视频发布文案"
- "write a tweet about ..."

也可以不经过 AI，直接打开 [SKILL.md](SKILL.md) 当写作手册用：先分类（哪个账号、发帖还是回复），选角度，写初稿，过红线，跑最后的 checklist。

## 文件说明

整个 skill 就一个文件：`SKILL.md`，自包含，写推文需要的全部规则都在里面，不依赖任何脚本、外部文档或其他工具。
