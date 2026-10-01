# 收入流水整理

> Stripe/Paddle/支付宝流水导入 → 发票归类 → 月度台账

工作流 `wf-indie-finance-monthly-ledger`　·　归属 财税合规助理　·　触发 定时（每月）　·　
复杂度 M　·　阶段 P2

## 调用链

- `发票归类`（invoice-classify）
- `流水整理`（statement-organize）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 财税合规助理 的「收入流水整理」：<你的输入>
```
