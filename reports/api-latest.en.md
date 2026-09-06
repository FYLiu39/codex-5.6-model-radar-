# Codex Radar API Monitor — English

[简体中文](api-latest.zh-CN.md) · [Project home](../README.md) · [API history CSV](../data/api/model_iq_history.csv) · [Monitor status](../data/api/monitor_status.json)

**Last successful check:** `2026-09-06T18:39:37+00:00`  
**Current API snapshot:** `6a5626dfaec5a592`  
**Source observation:** `2026-09-02T20:11:35.648389+08:00`  
**New snapshot detected:** no; the source returned the same snapshot  
**Models returned:** 11

> “Last successful check” confirms that the automation reached the API. “Source observation” is supplied by the upstream endpoint and may be older.

> This is a model-level summary from the Codex Radar API, not the project's task-level difficulty-weighted score.

## Current API model summary

| Rank | Model tier | Source score | Passed | Tasks | Cost | Total tokens | Wall time |
|---:|---|---:|---:|---:|---:|---:|---:|
| 1 | Luna Max | 109 | 81/112 | 112 | $54.26 | 2,175,117,762 | 76.66h |
| 2 | Terra Max | 106.3 | 79/112 | 112 | $420.43 | 1,244,001,980 | 58.89h |
| 3 | Gpt-5.5 Xhigh | 104.9 | 78/112 | 112 | $638.89 | 891,390,119 | 43.46h |
| 4 | Sol Xhigh | 102.2 | 76/112 | 112 | $578.85 | 826,265,228 | 46.38h |
| 5 | Sol High | 98.2 | 73/112 | 112 | $469.80 | 582,870,219 | 36.89h |
| 6 | Sol Medium | 95.5 | 71/112 | 112 | $312.43 | 414,988,420 | 27.15h |
| 7 | Gpt-5.5 High | 86.1 | 64/112 | 112 | $397.69 | 536,610,118 | 27.89h |
| 8 | Terra Xhigh | 86.1 | 64/112 | 112 | $210.68 | 587,416,643 | 36.41h |
| 9 | Terra High | 80.7 | 60/112 | 112 | $122.20 | 322,218,098 | 25.45h |
| 10 | Sol Low | 79.4 | 59/112 | 112 | $170.73 | 208,709,234 | 18.68h |
| 11 | Luna High | 68.6 | 51/112 | 112 | $22.49 | 811,105,802 | 34.54h |

## Interpretation

- The endpoint provides model-level `score`, pass counts, task counts, tokens, wall time, and estimated cost.
- It does not expose the ten task-level outcomes, so `Weighted /100` cannot be recomputed from this API summary alone.
- Task-weighted rankings remain based on the repository's task matrix and weight snapshots; this report monitors the latest API summary.
- When source data is unchanged, the automation still updates its heartbeat without presenting it as a new benchmark batch.
- The raw API response is not stored in the public repository; only required model-summary fields are archived.

Archived API snapshots: **410**.
