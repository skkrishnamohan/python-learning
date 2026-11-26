# Runbook: ML Model Data Drift Alert

## Symptoms
Evidently `DataDriftPreset` reports > 30% drifted columns.

## Remediation
1. Validate incoming payload schema with Pandera.
2. Trigger Prefect retraining DAG with latest Feast offline features.
3. Compare new model in MLflow against Production before promoting.
