---
name: ecommerce-growth-diagnostician
description: "分析独立站漏斗、利润与增长瓶颈，并制定低预算验证实验时使用"
---

# 独立站增长诊断

## When to use

分析独立站漏斗、利润与增长瓶颈，并制定低预算验证实验时使用；页面改版实施交给CRO技能。

## Preconditions

确认输入、当前版本、可用工具及本次授权范围。历史案例只作方法依据，不能替代当前验证。缺少关键输入时先做可独立完成的只读检查，再列阻塞。

## Procedure

1. 确认业务目标、时间区间、时区、币种、归因窗口和授权聚合数据源，不采集客户级数据。
2. 统一会话、加购、结账、订单、退款、收入、成本、运费、广告费口径，给分母、去重及排除项。
3. 检查缺值、零分母、税费/退款和币种，缺数据记UNKNOWN，不从文案收益主张倒推出真实业绩。
4. 按漏斗断点、单位经济性与证据置信度排序；区分相关性与原因。
5. 提出7/14/30天实验，说明假设、对照、主指标、护栏、预算上限及停止条件；没有实验数据不声明提升。

## Tool permissions

聚合数据读取与本地计算；不投放、不修改预算、不拉客户明细。

## Failure handling

缺数据给数据请求清单；口径冲突先修正，不保证利润。

## Deliverables

按下方输出契约交付本技能步骤中要求的清单、草稿/方案及证据；未执行项单列。

## Acceptance criteria

公式、分母、币种和时间范围可追溯；每项实验有停止条件；效果只有实测才PASS。

## Hard boundaries

不泄露密钥、客户隐私或非公开商业资料，不覆盖用户已有工作。读取权限不等于外发权限；生产变更按用户明确授权执行。

## Response contract

输出 `STATUS`、`SCOPE`、`EVIDENCE`、`CHANGES`、`TESTS RUN`、`OPEN RISKS`、`NEXT HUMAN ACTION`。逐项区分 PASS / NEED FIX / BLOCKED / NOT VERIFIED；历史记录、mock、本次本地与平台实测分列。

## Evidence and examples

阅读 [历史案例](references/cases.md) 时只加载与任务相关的案例；证据索引见其中链接。
