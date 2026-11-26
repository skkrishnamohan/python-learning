# Runbook: High CPU & API Latency Spike

## Symptoms
CPU > 85% and p95 latency > 300ms.

## Remediation
1. Check HorizontalPodAutoscaler (`kubectl get hpa`).
2. Scale replicas using Kubernetes Python Client or `kubectl scale`.
3. Verify Gunicorn worker count matches container CPU limits.
