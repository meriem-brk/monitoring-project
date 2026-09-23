# Monitoring Stack with Docker

A full monitoring stack using Prometheus, Grafana, Loki, cAdvisor, and Node Exporter.

## Services

- **Prometheus** - Metrics collection (port 9090)
- **Grafana** - Visualization dashboards (port 3000)
- **Node Exporter** - System metrics (port 9100)

## Usage

To start the monitoring stack, run:

```bash
docker compose up -d
```

Access Grafana at: http://localhost:300
