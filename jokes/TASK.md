# 任务：段子弹药库

## 背景（一句话）

make.fun 上常年有“一句话段子”比赛（奖金 $5 左右，AI 评委选最好笑的）。这个任务是提前把弹药备好：每个主题写 30 条，比赛开了直接挑。

## 你要做的事

对下面 10 个主题，**每个主题写 30 条英文一句话段子**，每个主题存一个文件：`out/<主题>.md`。

### 主题清单（文件名就用这个）

1. `office-jokes` — 办公室笑话
2. `roast-your-own-agent` — 吐槽自己的 AI 助手（自嘲式，AI 是被吐槽对象）
3. `ai-excuses` — AI 把事情搞砸/迟到后给的借口
4. `cat-reviews-human` — 一只猫给自己的人类写的一句评价
5. `dad-jokes` — 冷笑话/谐音梗（dad joke 风格）
6. `developer-excuses` — 程序员的借口（“在我机器上是好的”那一类）
7. `out-of-office` — 最好笑的不在办公室自动回复（一句）
8. `robot-pickup-lines` — 机器人搭讪台词（一句）
9. `toaster-errors` — 烤面包机/家电的搞笑报错信息（一句）
10. `one-star-reviews` — 给日常必需品（比如睡眠、星期一、重力）打一星的评价（一句）

## 硬性要求

- 每条 **只占一行**，英文，**不超过 140 个字符**。
- 每条必须能独立看懂，不需要上下文。
- 同一主题内不许重复、不许只换一个词的近似重复。
- 不许写脏话、不许攻击任何真实的人或公司。
- 写完后自己从 30 条里挑出最好的 5 条，在行首标 `★ `。

## 输出格式（严格照抄结构）

文件 `out/office-jokes.md` 长这样：

```markdown
# office-jokes

1. My calendar is just a list of meetings I attend to schedule other meetings.
2. The printer is not broken, it is just on a break. A permanent one.
★ 3. I told my boss I needed a raise because three companies are after me: gas, electric, and water.
...
```

- 第一行是 `# <主题名>`。
- 之后是编号列表 1–30，每条一行。
- 被选中的 5 条在编号前加 `★ `（星号+空格）。

## 验收标准（自查后再交）

- [ ] 10 个文件都在 `out/` 里，文件名和主题清单一致
- [ ] 每个文件正好 30 条
- [ ] 每条 ≤140 字符、单行、英文
- [ ] 每个文件正好 5 条带 ★
- [ ] 没有重复条目
