> # Monitoring Stack with docker
> 
> A full monitoring stack using Prometheus,Grafana, and Node exporter.
> 
> ## Services
> - **Prometheus** - Metrics collection (port 9090)
> - **Grafana** - Visualization dashboards (port 3000)
> - **Node Exporter** - System metrics (port 9100)
> 
> ## Usage
> '''bash
> docker compose up -d
Access Grafana at:http://localhost:3000
>
> ## 📊 Dashboards & Observability Overview

| 🖥️ Node Exporter (System Overview) | 🖥️ Node Exporter (CPU & RAM) |
| :---: | :---: |
| ![Node Exporter 1](assets/screenshots/node-exporter1.png) | ![Node Exporter 2](assets/screenshots/node-exporter2.png) |

| 🖥️ Node Exporter (Metrics Detail) | 🐳 cAdvisor (Containers Monitoring) |
| :---: | :---: |
| ![Node Exporter 3](assets/screenshots/node-exporter3.png) | ![cAdvisor](assets/screenshots/cAdvisor.png) |

| 📝 Loki Logs & Exploration | ⚙️ Process Exporter |
| :---: | :---: |
| ![Logs](assets/screenshots/logs.png) | ![Processes](assets/screenshots/processes.png) |

| 🌐 Blackbox Exporter (Probe Metrics) | 🌐 Blackbox Exporter (Status) |
| :---: | :---: |
| ![Blackbox Exporter](assets/screenshots/blackbox-exporter.png) | ![Blackbox Exporter 1](assets/screenshots/blackbox-exporter1.png) |

