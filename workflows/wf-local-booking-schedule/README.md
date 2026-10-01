# 技师/场地智能排班

> 当日预约 → 排班表 → 负荷均衡调整建议

工作流 `wf-local-booking-schedule`　·　归属 预约排班调度员　·　触发 定时（每日 6:30）　·　
复杂度 M　·　阶段 P1

## 调用链

- `日历排班引擎`（shift-calendar-engine）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 预约排班调度员 的「技师/场地智能排班」：<你的输入>
```
