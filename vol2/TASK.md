# 任务：第一批弹药扩容（每个主题再来一整套）

## 背景（一句话）

`jokes/` 和 `one-word/` 里的弹药已经各有一套。这个任务是给每个主题**再写一整套新的**，挑选余地翻倍。

## 你要做的事

### A. jokes 的 10 个主题，每个再写 30 条

主题（和 `../jokes/TASK.md` 里完全一样）：office-jokes、roast-your-own-agent、ai-excuses、cat-reviews-human、dad-jokes、developer-excuses、out-of-office、robot-pickup-lines、toaster-errors、one-star-reviews。

- 规矩和 `../jokes/TASK.md` 完全相同：每条单行、英文、≤140 字符、每套挑 5 条标 ★。
- **关键：先读 `../jokes/out/<主题>.md` 里已有的 30 条，新写的 30 条不许和它们重复，也不许只是换一个词的近似重复——要换角度、换梗。**
- 输出到 `out/<主题>-2.md`，格式与第一套相同（第一行 `# <主题>-2` 也可以写 `# <主题>`，统一写 `# <主题>-2`）。

### B. one-word 的 5 个主题，每个再写 50 条

主题（和 `../one-word/TASK.md` 里完全一样）：one-word-for-wifi、one-word-from-grandma、one-word-for-the-boss、one-emoji-one-smile、one-word-first-thought。

- 规矩和 `../one-word/TASK.md` 完全相同：表格格式、候选只能一个词/一个 emoji、理由 ≤8 个英文单词、每套挑 10 条标 ★。
- **关键：先读 `../one-word/out/<主题>.md` 里已有的 50 条候选，新候选不许和它们重复。**
- 输出到 `out/<主题>-2.md`。

## 验收标准（自查后再交）

- [ ] A 部分 10 个文件、B 部分 5 个文件，都在 `out/` 里
- [ ] 条数、字数、★ 数量与第一批的要求一致
- [ ] 与第一批零重复（候选词/段子本体都不能撞）
