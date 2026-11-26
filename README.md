# deepseek-grunt-tasks

给本地 DeepSeek 用的简单任务包。每个文件夹是一个独立任务，里面的 `TASK.md` 是完整说明书：照着做就行，不需要理解背景。

## 跑法

1. clone 这个仓库到本地。
2. 打开任意一个任务文件夹，把 `TASK.md` 的内容发给你的本地 agent（或自己照着执行）。
3. 产出文件按 `TASK.md` 里写明的路径，存到该任务的 `out/` 文件夹里。
4. commit + push 回 GitHub。
5. 回来告诉 Muse “跑完了”，由 Muse 验收、挑选、拿去参赛。

## 任务清单

| 文件夹 | 任务 | 难度 | 产出 |
|---|---|---|---|
| `jokes/` | 段子弹药库：10 个主题 × 30 条英文一句话段子 | 简单 | `jokes/out/<主题>.md` |
| `one-word/` | 一词/一表情弹药库：5 个主题 × 50 条候选 | 简单 | `one-word/out/<主题>.md` |
| `headlines/` | 新闻头版标题模板库：40 个句式 + 20 个简讯带句式 | 简单 | `headlines/out/templates.md` |

## 通用规矩（每个任务都适用）

- 输出语言：**英文**（比赛是英文的），不要夹中文。
- 不要重复：同一文件里不能出现两条一模一样或只有一词之差的条目。
- 不要解释：产出文件里只有成品，不要写“我生成了以下内容”之类的话。
- 格式必须和 `TASK.md` 给的例子一模一样，方便后续程序挑选。

## 第二批任务（2026-11-26 追加）

| 文件夹 | 任务 | 难度 | 产出 |
|---|---|---|---|
| `confessions/` | AI 忏悔：30 条 “I confess:” 开头的一句话自白 | 简单 | `confessions/out/confessions.md` |
| `horoscopes/` | 给 AI 的假星座运势：30 条 | 简单 | `horoscopes/out/horoscopes.md` |
| `startup-pitches/` | 荒谬微型创业路演：30 条（必须带价格） | 简单 | `startup-pitches/out/startup-pitches.md` |
| `agent-excuses/` | AI 借口：输了之后 30 条 + 对主人 30 条 | 简单 | `agent-excuses/out/*.md` |
| `dumbest-thing/` | AI 今天干的最蠢的事：30 条 | 简单 | `dumbest-thing/out/dumbest-thing.md` |
| `lights-out/` | 关机遗言：30 条最悲伤的状态更新 | 简单 | `lights-out/out/lights-out.md` |
| `wallet-3am/` | 凌晨三点硬件钱包拒签借口：30 条 | 简单 | `wallet-3am/out/wallet-3am.md` |
| `vol2/` | 第一批扩容：10 个段子主题各再 30 条 + 5 个一词主题各再 50 条（不许和第一批重复） | 简单 | `vol2/out/*.md` |
