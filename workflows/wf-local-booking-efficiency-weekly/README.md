# 排班效率周报

> 上座率热力图 → 低谷时段促销建议

工作流 `wf-local-booking-efficiency-weekly`　·　归属 预约排班调度员　·　触发 定时（每周一）　·　
复杂度 S　·　阶段 P2

## 调用链

- `需求预测`（demand-forecast）
- `消息通知`（notification-dispatcher）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 预约排班调度员 的「排班效率周报」：<你的输入>
```
