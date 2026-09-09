# Codex Radar API Monitor — English

[简体中文](api-latest.zh-CN.md) · [Project home](../README.md) · [API history CSV](../data/api/model_iq_history.csv) · [Monitor status](../data/api/monitor_status.json)

**Last successful check:** `2026-09-09T01:16:22+00:00`  
**Current API snapshot:** `dd2a9a1febfe0c91`  
**Source observation:** `2026-09-02T20:11:35.648389+08:00`  
**New snapshot detected:** no; the source returned the same snapshot  
**Models returned:** 11

> “Last successful check” confirms that the automation reached the API. “Source observation” is supplied by the upstream endpoint and may be older.

> This is a model-level summary from the Codex Radar API, not the project's task-level difficulty-weighted score.

## Current API model summary

| Rank | Model tier | Source score | Passed | Tasks | Cost | Total tokens | Wall time |
|---:|---|---:|---:|---:|---:|---:|---:|
| 1 | Luna Max | 107.6 | 80/112 | 112 | $54.34 | 2,109,560,673 | 74.58h |
| 2 | Terra Max | 106.3 | 79/112 | 112 | $420.54 | 1,243,148,712 | 58.93h |
| 3 | Gpt-5.5 Xhigh | 104.9 | 78/112 | 112 | $638.91 | 898,444,667 | 43.51h |
| 4 | Sol Xhigh | 100.9 | 75/112 | 112 | $577.41 | 828,153,093 | 46.74h |
| 5 | Sol High | 99.5 | 74/112 | 112 | $467.89 | 585,730,695 | 36.79h |
| 6 | Sol Medium | 98.2 | 73/112 | 112 | $312.47 | 417,314,109 | 27.57h |
| 7 | Gpt-5.5 High | 84.7 | 63/112 | 112 | $397.47 | 537,503,257 | 28.08h |
| 8 | Terra Xhigh | 84.7 | 63/112 | 112 | $210.74 | 582,880,325 | 36.09h |
| 9 | Terra High | 82.1 | 61/112 | 112 | $122.07 | 323,246,167 | 25.46h |
| 10 | Sol Low | 79.4 | 59/112 | 112 | $170.70 | 209,313,734 | 18.72h |
| 11 | Luna High | 68.6 | 51/112 | 112 | $22.49 | 811,105,802 | 34.54h |

## Interpretation

- The endpoint provides model-level `score`, pass counts, task counts, tokens, wall time, and estimated cost.
- It does not expose the ten task-level outcomes, so `Weighted /100` cannot be recomputed from this API summary alone.
- Task-weighted rankings remain based on the repository's task matrix and weight snapshots; this report monitors the latest API summary.
- When source data is unchanged, the automation still updates its heartbeat without presenting it as a new benchmark batch.
- The raw API response is not stored in the public repository; only required model-summary fields are archived.

Archived API snapshots: **414**.
