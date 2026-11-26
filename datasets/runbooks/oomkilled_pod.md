# Runbook: OOMKilled Pod (Exit Code 137)

## Symptoms
Pod restarts repeatedly with `OOMKilled` status.

## Root Cause
Container exceeded `resources.limits.memory`.

## Remediation
1. Inspect memory usage with `kubectl top pod`.
2. Increase `resources.limits.memory` in deployment YAML.
3. Check for Python memory leaks (e.g., loading large models per request instead of at startup).
