# 任务：一词 / 一表情弹药库

## 背景（一句话）

make.fun 上有一类比赛只比拼**一个词**或**一个表情**（奖金 $5 左右）。这个任务是提前把候选备好：每个主题 50 条，比赛开了直接挑。

## 你要做的事

对下面 5 个主题，**每个主题写 50 条候选**，每个主题存一个文件：`out/<主题>.md`。

### 主题清单（文件名就用这个）

1. `one-word-for-wifi` — 用一个词形容你的 Wi-Fi
2. `one-word-from-grandma` — 奶奶会对你说的一个词
3. `one-word-for-the-boss` — 送给老板的一个词
4. `one-emoji-one-smile` — 一个能让人笑的表情符号
5. `one-word-first-thought` — 早上醒来脑子里蹦出的第一个词

## 硬性要求

- 候选部分：主题 1/2/3/5 只能是**一个英文单词**（不许词组）；主题 4 只能是**一个 emoji**。
- 每条配一句**不超过 8 个英文单词**的理由（为什么这个候选好笑/贴切）。
- 同一主题内候选不许重复。
- 写完后自己挑出最好的 10 条，在表格行首的序号格里标 `★`。

## 输出格式（严格照抄结构）

文件 `out/one-word-for-wifi.md` 长这样：

```markdown
# one-word-for-wifi

| # | Candidate | Why it works |
|---|---|---|
| 1 | buffering | it is always the current status |
| ★2 | betrayal | it leaves during the final episode |
| 3 | seasonal | strong in winter, gone by summer |
...
```

- 第一行是 `# <主题名>`。
- 之后是表格，正好 50 行候选。
- 被选中的 10 行，序号写成 `★<数字>` 这种形式（如 `★2`）。

## 验收标准（自查后再交）

- [ ] 5 个文件都在 `out/` 里，文件名和主题清单一致
- [ ] 每个文件正好 50 条候选
- [ ] 候选确实只有一个词 / 一个 emoji
- [ ] 每条理由 ≤8 个英文单词
- [ ] 每个文件正好 10 条带 ★
