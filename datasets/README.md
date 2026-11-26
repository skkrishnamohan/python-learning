# Datasets Directory

Realistic DevOps, MLOps, AIOps, and LLMOps datasets used across the 62-day curriculum.

| File | Format | Rows / Size | Used In |
|------|--------|-------------|---------|
| [servers.csv](servers.csv) | CSV | 200 servers | Days 24, 26, 28, 29, 36, 39 |
| [server_metrics_timeseries.csv](server_metrics_timeseries.csv) | CSV | 720 hourly rows (30 days) | Days 24, 25, 53, 54 |
| [app_logs.jsonl](app_logs.jsonl) | JSON Lines | 150 structured log events | Days 19, 44, 54 |
| [ml_experiments.csv](ml_experiments.csv) | CSV | 12 experiment runs | Days 24, 27, 34 |
| [cloud_costs.csv](cloud_costs.csv) | CSV (dirty: NaNs, negatives, duplicates) | 8 billing rows | Days 25, 36 |
| [devops_telemetry.db](devops_telemetry.db) | SQLite (`servers`, `deployments`) | 2 tables | Day 25 |
| [runbooks/](runbooks/) | Markdown | 3 SRE runbooks | Days 57, 62 |
