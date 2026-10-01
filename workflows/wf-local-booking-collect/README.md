# 在线预约受理

> 意图识别 → 项目/技师/时间匹配 → 确认

工作流 `wf-local-booking-collect`　·　归属 预约排班调度员　·　触发 事件（客户微信/小程序发起）　·　
复杂度 M　·　阶段 P1

## 调用链

- `日历排班引擎`（shift-calendar-engine）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 预约排班调度员 的「在线预约受理」：<你的输入>
```
