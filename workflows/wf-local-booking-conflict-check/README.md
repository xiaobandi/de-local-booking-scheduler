# 冲突与超售检测

> 实时冲突扫描 → 老板确认改派方案

工作流 `wf-local-booking-conflict-check`　·　归属 预约排班调度员　·　触发 事件（新预约写入）　·　
复杂度 S　·　阶段 P1

## 调用链

- `日历排班引擎`（shift-calendar-engine）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 预约排班调度员 的「冲突与超售检测」：<你的输入>
```
