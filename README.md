# 投资学实践 1：资产的收益和风险度量

北京师范大学 2026 秋季学期。完整计算在 `作业.ipynb`，报告正文是 `报告.qmd`。

仓库：<https://github.com/aylmerwawa/investments-lab1-return-risk>

## 数据

把课程发放的 `实践1数据-股指黄金比特币-2006至今.xlsx` 放到本目录（与 notebook 同级）。该文件不进 git。

窗口默认 `2006-01-01`–`2025-12-31`。`SHORT_WINDOW = True` 为蓝字原理版（2024–2025），提交用 20 年。

## 运行

conda 环境 `ml`（pandas / numpy / scipy / matplotlib / seaborn）。

```bash
jupyter notebook 作业.ipynb
```

表和图写入 `结果/`。命名与题号对齐：`01` 收益与波动，`02` VaR，`03` 相关。

```bash
quarto render 报告.qmd --to pdf
```
