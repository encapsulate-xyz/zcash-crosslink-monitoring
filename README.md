# zcash-crosslink-monitoring
Grafana dashboards and alerting rules for running a Zcash Crosslink finalizer and node, by Encapsulate.

## 📂 Repository Contents

```bash
.
├── zcash-node-dashboard.json   # Ready-to-import Grafana Dashboard
├── zcash-node-alerts.yml       # Prometheus Alerting Rules for Alertmanager
└── README.md                   # Documentation & Deployment Guide
```

## Import Grafana Dashboard
1. Open your Grafana instance.
2. Navigate to **Dashboards** → **New** → **Import Dashboard**.
3. Upload [`zcash-node-dashboard.json`](zcash-node-dashboard.json) or paste its contents.
4. Select your Prometheus data source from the dropdown.
5. Click **Import**!
