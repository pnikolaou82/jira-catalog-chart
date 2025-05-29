# Jira Helm Chart (Rancher Catalog Ready)

This Helm chart deploys Jira with support for multiple environments, RBAC controls, and variable schema via Rancher's `questions.yaml`.

## Usage

To deploy to Rancher:
1. Add this chart to your Rancher Git-based catalog.
2. Select the environment (dev, staging, prod) via UI or CLI:
   ```bash
   helm install jira -f values-dev.yaml .
