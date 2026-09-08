# Codex Radar API Monitor / API 自动监控

[简体中文](#简体中文) · [English](#english)

<a id="简体中文"></a>
# Codex Radar API 自动监控 — 简体中文

[English](api-latest.en.md) · [项目首页](../README.md) · [API 历史 CSV](../data/api/model_iq_history.csv) · [监控状态](../data/api/monitor_status.json)

**最近成功检查：** `2026-09-08T09:09:54+00:00`  
**当前 API 快照：** `a90a7fe32826f83f`  
**源站观测时间：** `2026-09-02T20:11:35.648389+08:00`  
**本次发现新快照：** 否；源站仍返回同一快照  
**返回模型数：** 11

> “最近成功检查”表示自动任务已正常访问 API；“源站观测时间”由上游接口提供，两者可能不同。

> 这是 Codex Radar API 返回的模型级摘要，不是本项目根据逐题矩阵计算的难度加权分。

## 当前 API 模型摘要

| 排名 | 模型档位 | 源站分数 | 通过 | 任务数 | 费用 | 总 Token | 耗时 |
|---:|---|---:|---:|---:|---:|---:|---:|
| 1 | Luna Max | 109 | 81/112 | 112 | $54.33 | 2,159,802,501 | 76.10h |
| 2 | Gpt-5.5 Xhigh | 106.3 | 79/112 | 112 | $638.88 | 897,369,629 | 43.40h |
| 3 | Terra Max | 106.3 | 79/112 | 112 | $420.54 | 1,243,148,712 | 58.93h |
| 4 | Sol Xhigh | 102.2 | 76/112 | 112 | $577.69 | 830,572,548 | 46.21h |
| 5 | Sol High | 98.2 | 73/112 | 112 | $469.38 | 581,026,729 | 36.49h |
| 6 | Sol Medium | 98.2 | 73/112 | 112 | $312.58 | 417,295,395 | 27.48h |
| 7 | Terra Xhigh | 84.7 | 63/112 | 112 | $210.70 | 582,211,902 | 36.45h |
| 8 | Gpt-5.5 High | 83.4 | 62/112 | 112 | $397.62 | 538,361,796 | 28.12h |
| 9 | Terra High | 82.1 | 61/112 | 112 | $122.09 | 322,611,430 | 25.42h |
| 10 | Sol Low | 79.4 | 59/112 | 112 | $170.70 | 209,313,734 | 18.72h |
| 11 | Luna High | 68.6 | 51/112 | 112 | $22.49 | 811,105,802 | 34.54h |

## 口径说明

- 当前接口提供模型级 `score`、通过数、任务数、Token、耗时和估算费用。
- 当前接口没有返回十道任务的逐题通过矩阵，因此不能仅凭 API 摘要重新计算 `加权分 /100`。
- 加权排名仍以仓库中的逐题数据和权重快照为准；本报告用于自动监控源站最新摘要。
- 源站数据未变化时，自动任务仍会更新监控心跳，但不会把它描述成新的模型测试批次。
- 原始 API 响应不写入公开仓库，只保存必要的模型摘要字段。

当前已归档 API 快照数：**411**。


---

<a id="english"></a>
# Codex Radar API Monitor — English

[简体中文](api-latest.zh-CN.md) · [Project home](../README.md) · [API history CSV](../data/api/model_iq_history.csv) · [Monitor status](../data/api/monitor_status.json)

**Last successful check:** `2026-09-08T09:09:54+00:00`  
**Current API snapshot:** `a90a7fe32826f83f`  
**Source observation:** `2026-09-02T20:11:35.648389+08:00`  
**New snapshot detected:** no; the source returned the same snapshot  
**Models returned:** 11

> “Last successful check” confirms that the automation reached the API. “Source observation” is supplied by the upstream endpoint and may be older.

> This is a model-level summary from the Codex Radar API, not the project's task-level difficulty-weighted score.

## Current API model summary

| Rank | Model tier | Source score | Passed | Tasks | Cost | Total tokens | Wall time |
|---:|---|---:|---:|---:|---:|---:|---:|
| 1 | Luna Max | 109 | 81/112 | 112 | $54.33 | 2,159,802,501 | 76.10h |
| 2 | Gpt-5.5 Xhigh | 106.3 | 79/112 | 112 | $638.88 | 897,369,629 | 43.40h |
| 3 | Terra Max | 106.3 | 79/112 | 112 | $420.54 | 1,243,148,712 | 58.93h |
| 4 | Sol Xhigh | 102.2 | 76/112 | 112 | $577.69 | 830,572,548 | 46.21h |
| 5 | Sol High | 98.2 | 73/112 | 112 | $469.38 | 581,026,729 | 36.49h |
| 6 | Sol Medium | 98.2 | 73/112 | 112 | $312.58 | 417,295,395 | 27.48h |
| 7 | Terra Xhigh | 84.7 | 63/112 | 112 | $210.70 | 582,211,902 | 36.45h |
| 8 | Gpt-5.5 High | 83.4 | 62/112 | 112 | $397.62 | 538,361,796 | 28.12h |
| 9 | Terra High | 82.1 | 61/112 | 112 | $122.09 | 322,611,430 | 25.42h |
| 10 | Sol Low | 79.4 | 59/112 | 112 | $170.70 | 209,313,734 | 18.72h |
| 11 | Luna High | 68.6 | 51/112 | 112 | $22.49 | 811,105,802 | 34.54h |

## Interpretation

- The endpoint provides model-level `score`, pass counts, task counts, tokens, wall time, and estimated cost.
- It does not expose the ten task-level outcomes, so `Weighted /100` cannot be recomputed from this API summary alone.
- Task-weighted rankings remain based on the repository's task matrix and weight snapshots; this report monitors the latest API summary.
- When source data is unchanged, the automation still updates its heartbeat without presenting it as a new benchmark batch.
- The raw API response is not stored in the public repository; only required model-summary fields are archived.

Archived API snapshots: **411**.

