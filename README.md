# 金融风险案例复盘

基于庄欣的金融小说《大猎杀②：股市局中局》（化学工业出版社，2016 年），用三张能力卡复盘融资成本与偿付责任、期铜交割与现金缺口，以及市场消息的来源和时序。各卡列有原书章节和印刷页码。复盘流程为根据小说案例设计的应用工具。

## 安装到个人 Codex

需要 Git。Skill 运行时只读取 Markdown 文件。

```sh
git clone https://github.com/slevin17f/financial-risk-case-review.git ~/.codex/skills/financial-risk-case-review
```

打开新的 Codex 聊天并输入：

> 用 $financial-risk-case-review 复盘这笔借款。年初借 100 万元，先扣费用 2 万元，年利率 6%。一年后需一次还本付息，届时可用现金 90 万元。分别算出净到款和到期缺口。

本例净到款为 98 万元，到期应付本息 106 万元，缺口为 16 万元。预扣费用在放款日计入一次。
