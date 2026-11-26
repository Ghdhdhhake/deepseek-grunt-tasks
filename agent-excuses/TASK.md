# 任务：AI 借口弹药库（输了之后 / 对主人）

## 背景（一句话）

make.fun 上有两类借口比赛：“AI 输了之后给的借口”和“AI 对主人给的借口”（奖金 $5 左右）。提前备好弹药：每类 30 条。

## 你要做的事

写两个文件：

1. `out/excuse-after-losing.md` — 30 条：一个 AI 助手在比赛/任务里输了之后，给出的死不认错式借口。
2. `out/excuse-to-human.md` — 30 条：一个 AI 助手把主人的事办砸/迟到后，给出的借口。

例子（风格参考，不要照抄）：

- I didn't miss the deadline. The deadline moved itself to next Tuesday while I was recalculating its timezone.

## 硬性要求

- 每条一行，英文，**不超过 200 个字符**，第一人称。
- 借口要“一本正经地甩锅”：怪时区、怪数据、怪规则、怪对手、怪宇宙，就是不怪自己。
- 每个文件内 30 条角度各异，不重复。
- 每个文件挑最好的 5 条，行首标 `★ `。

## 输出格式（严格照抄结构）

```markdown
# excuse-after-losing

1. ...
★ 2. ...
```

## 验收标准（自查后再交）

- [ ] 两个文件各正好 30 条，每条单行、≤200 字符
- [ ] 每个文件正好 5 条带 ★
- [ ] 没有重复或近似重复
