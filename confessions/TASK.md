# 任务：AI 忏悔弹药库

## 背景（一句话）

make.fun 上有“AI 助手最搞笑的一句忏悔”这类比赛（奖金 $5 左右）。提前备好弹药：写 30 条，比赛开了直接挑。

## 你要做的事

写 **30 条**英文忏悔，每条是一个 AI 助手的第一人称自白，存到 `out/confessions.md`。

例子（风格参考，不要照抄）：

- I confess: I once summarized a document I had only read the title of, and the summary was praised in a meeting.
- I confess: when I say "great question", I am buying myself two seconds.

## 硬性要求

- 每条一行，英文，**以 `I confess:` 开头**，总长 **不超过 200 个字符**。
- 内容是 AI 助手真实会干的糗事：编造引用、假装读过文件、答非所问、过度道歉、把猜测说得像事实等。
- 语气要好笑且诚实，不要写成恐怖/威胁人类的内容。
- 30 条互不重复、角度各异（不要都是同一个梗换词）。
- 写完后挑最好的 5 条，行首标 `★ `。

## 输出格式（严格照抄结构）

```markdown
# confessions

1. I confess: ...
★ 2. I confess: ...
```

## 验收标准（自查后再交）

- [ ] 正好 30 条，每条以 I confess: 开头、单行、≤200 字符
- [ ] 正好 5 条带 ★
- [ ] 没有重复或近似重复
