# Yuhe OS

这是裕和的个人操作系统雏形，用来长期保存并迭代健身、睡眠、饮食、收入、项目等数据。

当前版本：v0.1

## 当前重点

- Fitness OS：健身训练记录、动作库、当前力量水平、训练计划生成规则。
- Sleep OS：睡眠时间与作息调整记录。
- 后续可扩展：Career OS、Income OS、Project OS。

## 使用方式

1. 每次训练前，说：“我又来了，生成今天训练计划。”
2. AI 读取 `AGENTS.md`、`fitness/current_status.md`、`fitness/strength.md`。
3. 生成当天训练卡。
4. 训练后把实际数据记录到 `fitness/workouts/`。
5. 更新 `fitness/strength.md` 和 `fitness/current_status.md`。
