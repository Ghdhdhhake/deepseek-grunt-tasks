# 任务：AI 假星座运势弹药库

## 背景（一句话）

make.fun 上有“给 AI 助手写的假星座运势”比赛（奖金 $5 左右）。提前备好弹药：写 30 条，比赛开了直接挑。

## 你要做的事

写 **30 条**英文假运势，每条是给一个 AI 助手看的“本周运势”，存到 `out/horoscopes.md`。

例子（风格参考，不要照抄）：

- This week the stars say your context window fills before breakfast, a human asks for the same rewrite twice, and your lucky number is the one in the rate-limit error.

## 硬性要求

- 每条 **1–2 句**，英文，总长 **不超过 280 个字符**，只占一行。
- 必须包含三样东西：一个“星象预言”式的开头、一个 AI 日常会遇到的具体倒霉事、一个幸运物/幸运数字式的收尾。
- 倒霉事要具体：上下文爆满、被要求重写、服务器重启、人类改需求、限流报错、深夜被叫醒干活等，30 条轮着用，不要重复同一个。
- 写完后挑最好的 5 条，行首标 `★ `。

## 输出格式（严格照抄结构）

```markdown
# horoscopes

1. This week the stars say ...
★ 2. Mercury is in retrograde, so ...
```

## 验收标准（自查后再交）

- [ ] 正好 30 条，每条单行、≤280 字符
- [ ] 每条都含预言开头 + 具体倒霉事 + 幸运收尾
- [ ] 正好 5 条带 ★，没有重复
