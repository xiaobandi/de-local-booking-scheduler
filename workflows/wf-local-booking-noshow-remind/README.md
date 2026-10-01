# 爽约预测+候补补位

> 历史爽约特征打分 → 高风险预约提前确认 → 爽约后候补名单自动通知

工作流 `wf-local-booking-noshow-remind`　·　归属 预约排班调度员　·　触发 定时（每日两次扫描）　·　
复杂度 L　·　阶段 P1

## 调用链

- `需求预测`（demand-forecast）
- `消息通知`（notification-dispatcher）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 预约排班调度员 的「爽约预测+候补补位」：<你的输入>
```
