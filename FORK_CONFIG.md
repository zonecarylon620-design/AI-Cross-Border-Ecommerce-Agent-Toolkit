# 本 Fork 配置说明

- **来源**：Fork 自 [`heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit`](https://github.com/heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit)（MIT License）
- **用途**：将仓库的 7 个 AI Agent 工作流应用于**灯具类目**的跨境电商运营
- **使用路径**：读根目录 `SKILL.md` 路由 → 打开对应 `Agents/<模块>/SKILL.md` → 填写 `templates/` 输入模板 → 跑 `scripts/` 出确定性指标 → 过校验后交付

## 待补充（使用前填写）

| 项目 | 现状 | 需要你补充 |
|---|---|---|
| 目标站点与市场 | 默认模板专精 Shopee 巴西站 / Mercado Livre（PT-BR） | 你的灯具计划入驻的站点（如 Shopify / 东南亚站） |
| 目标市场母语 | PT-BR / ES / EN | 你面向市场使用的母语 |
| 平台费率与税费口径 | 定价模型含 5 平台费率预设、未含税费 | 按目标站点的实际费率与税率复核 |
| 灯具类目模板 | 现有案例为滑板车 / 充电宝 / 宠物包 / 空气炸锅 / 保温袋，暂无灯具 | 灯具类目专用配置维度表（可参考 `docs/` 方法论自建） |

## 同步上游

- 上游更新：在 GitHub 仓库页点击 **Fetch upstream** 即可拉取，`FORK_CONFIG.md` 为本 Fork 独有文件，不会与上游冲突
- 本文件仅做使用配置记录，不改动上游交付物内容
