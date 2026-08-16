# 审查报告

## 结论

- 总体：PASS / FAIL / BLOCKED / NOT_TESTABLE
- 风险等级：R0 / R1 / R2 / R3
- 一句话结论：
- 结论适用范围：
- 同时存在的 BLOCKED / NOT_TESTABLE 项：
- 仍需谁做什么：

## 范围与基线

- 任务合同：
- commit / 分支 / Git dirty 状态：
- 审查目录、模块、角色和数据：
- 排除范围：
- 环境、工具及版本：
- 未跟踪文件如何纳入审查：

## 发现摘要

| 状态 | P0 | P1 | P2 | P3 | 合计 |
| --- | ---: | ---: | ---: | ---: | ---: |
| candidate | 0 | 0 | 0 | 0 | 0 |
| confirmed | 0 | 0 | 0 | 0 | 0 |
| fixing | 0 | 0 | 0 | 0 | 0 |
| fixed_unverified | 0 | 0 | 0 | 0 | 0 |
| verified | 0 | 0 | 0 | 0 | 0 |
| accepted | 0 | 0 | 0 | 0 | 0 |
| closed | 0 | 0 | 0 | 0 | 0 |
| false_positive | 0 | 0 | 0 | 0 | 0 |
| dismissed | 0 | 0 | 0 | 0 | 0 |
| blocked | 0 | 0 | 0 | 0 | 0 |
| not-testable | 0 | 0 | 0 | 0 | 0 |

详细问题账本：

## 验收层级

| 层级 | 状态 | 证据 | 缺口 |
| --- | --- | --- | --- |
| 静态检查：type/lint/build | pass/fail/blocked/not-testable/not-applicable |  |  |
| 聚焦与相关全量测试 |  |  |  |
| 差异与正确结果对照 |  |  |  |
| 独立 AI Review |  |  |  |
| 安全专项 |  |  |  |
| 真实浏览器与角色 |  |  |  |
| 实际运行环境 |  |  |  |
| 生产发布 |  |  |  |
| 人工与业务接受 |  |  |  |

任何一层的 PASS 都不能自动填充另一层。

本来不属于合同范围的层写 `not-applicable` 并说明理由；本应判断但当前没有合法验证方法时写 `not-testable`。

## 变更与恢复

- 改动摘要：
- 未改变的不变量：
- 固定制品或哈希：
- 备份与恢复验证：
- 回滚对象、步骤和触发条件：

## 未决风险与下一步

- 未决风险：
- 被接受风险及责任人和期限：
- BLOCKED / NOT_TESTABLE 的解除条件：
- 下一步唯一动作：
