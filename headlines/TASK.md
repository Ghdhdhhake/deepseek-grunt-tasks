# 任务：新闻头版标题模板库

## 背景（一句话）

有一类每日比赛要用一张图总结当天世界新闻，图上需要大标题和底部简讯带。这个任务是提前备好**可套用的英文标题句式**：以后每天把当天新闻往句式里一填就能用。

## 你要做的事

在 `out/templates.md` 里写两部分：

### A. 大标题句式 × 40

- 每个句式是一个填空模板，用 `<尖括号>` 标出要填的部分，比如 `<COUNTRY>`、`<EVENT>`、`<PLACE>`、`<NUMBER>`。
- 每个句式下面给 **2 个填好的例子**（例子用虚构但合理的新闻，不要用真实人名）。
- 句式要覆盖不同新闻类型：冲突/安全、经济/市场、科技、太空/科学、外交、气候/灾害、体育、社会。

### B. 简讯带句式 × 20

- 简讯带是头版底部一行里塞 3 条短新闻的格式，每条是一个短句。
- 给 20 个**成对示例**：每个示例是一整行简讯带（含 3 条短新闻，用 ` - ` 分隔），新闻内容虚构但合理。
- 每条短新闻不超过 9 个英文单词。

## 硬性要求

- 全英文。
- 句式之间不许只是换个名词的近似重复，要真的换结构（陈述式、引语式、数字式、问句式等都可以）。
- 不要用真实政治人物、真实公司的名字举例。

## 输出格式（严格照抄结构）

```markdown
# Headline templates

## A. Headlines

### 1. <COUNTRY> SAYS <EVENT> IN <PLACE>
- Example: FRANCE SAYS STORM DAMAGE IN BISCAY WORSE THAN EXPECTED
- Example: JAPAN SAYS FIRST SNOWFALL IN TOKYO BREAKS NOVEMBER RECORD

### 2. ...

## B. Ticker lines

1. FLOODS CLOSE THREE AIRPORTS IN SPAIN - CITY MARATHON BREAKS ENTRY RECORD - LOCAL BAKERY WINS NATIONAL PRIZE
2. ...
```

## 验收标准（自查后再交）

- [ ] A 部分正好 40 个句式，每个带 2 个例子
- [ ] B 部分正好 20 行简讯带，每行 3 条、每条 ≤9 个词
- [ ] 没有真实人名/公司名
- [ ] 句式结构互不重复
