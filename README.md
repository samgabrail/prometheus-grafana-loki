# Overview

A monitoring stack with Prometheus, Loki, and Grafana. Using this with Vault 202 course. CAREFUL if making modifications!

## Start the Monitoring stack

```bash
docker compose up -d
```

## Grafana Dashboards

Import the `vault.json` dashboard located in the folder `grafana/provisioning/dashboards` into Grafana.

Create a couple of panels for logs. One for System logs and the other for Audit logs.

