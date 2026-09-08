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
