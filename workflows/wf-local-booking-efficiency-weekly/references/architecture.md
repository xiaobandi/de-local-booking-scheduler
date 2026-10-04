# 排班效率周报 · 速查

| 项 | 内容 |
|---|---|
| slug | `wf-local-booking-efficiency-weekly` |
| 层级 | L2-workflow |
| 归属 | 预约排班调度员（`de-local-booking-scheduler`） |
| 复杂度 / 阶段 | S / P2 |
| 能力族 | — |
| 定义出处 | — |
| 复用情况 | — |

## 调用的 SKILL

| 技能 | slug | 来源 |
|---|---|---|
| 需求预测 | `demand-forecast` | 本仓 |
| 消息通知 | `notification-dispatcher` | 本仓 |

## 字段

| 项 | 内容 |
|---|---|
| 必需输入 | 本工作流的起始材料（见 `SKILL.md`「执行步骤」第 1 步）；用户身份与目标平台/渠道 |
| 可选输入 | 历史产出；账号人设；渠道规则；上一周期的数据 |
| 产出 | 低谷时段促销建议 |
| 脚本 | 无 |
