\# 🚀 DevOps Monitoring Stack



!\[Docker](https://img.shields.io/badge/Docker-Containerized-blue)

!\[Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-orange)

!\[Grafana](https://img.shields.io/badge/Grafana-Dashboard-red)

!\[Node Exporter](https://img.shields.io/badge/Node%20Exporter-Metrics-green)



\## 📌 Overview



A production-style monitoring and observability stack built using \*\*Prometheus\*\*, \*\*Grafana\*\*, and \*\*Node Exporter\*\*.



This project demonstrates how infrastructure metrics can be collected, stored, and visualized in real time using containerized services.



\---



\## 🏗️ Architecture



```text

&#x20;                   ┌──────────────┐

&#x20;                   │    USER      │

&#x20;                   └──────┬───────┘

&#x20;                          │

&#x20;                          ▼

&#x20;                ┌──────────────────┐

&#x20;                │     Grafana      │

&#x20;                │   Dashboards     │

&#x20;                └──────┬───────────┘

&#x20;                       │

&#x20;                       ▼

&#x20;                ┌──────────────────┐

&#x20;                │    Prometheus    │

&#x20;                │ Metrics Storage  │

&#x20;                └──────┬───────────┘

&#x20;                       │

&#x20;                       ▼

&#x20;                ┌──────────────────┐

&#x20;                │  Node Exporter   │

&#x20;                │ Host Metrics     │

&#x20;                └──────┬───────────┘

&#x20;                       │

&#x20;                       ▼

&#x20;                ┌──────────────────┐

&#x20;                │ Windows/Linux VM │

&#x20;                └──────────────────┘

```



\---



\## 🛠️ Tech Stack



\* Docker

\* Docker Compose

\* Prometheus

\* Grafana

\* Node Exporter



\---



\## 🚀 Services



| Service       | Port | Purpose                 |

| ------------- | ---- | ----------------------- |

| Grafana       | 3000 | Visualization Dashboard |

| Prometheus    | 9090 | Metrics Collection      |

| Node Exporter | 9100 | Host Metrics Export     |



\---



\## ▶️ Run Locally



```bash

docker compose up -d

```



Verify containers:



```bash

docker ps

```



\---



\## 📊 Monitoring Features



\* Real-time CPU Monitoring

\* Memory Utilization Tracking

\* Disk Usage Monitoring

\* Network Traffic Analysis

\* Filesystem Metrics

\* System Uptime Tracking

\* Infrastructure Observability



\---



\## 📈 Grafana Dashboard



Dashboard Imported:



\*\*Node Exporter Full (Dashboard ID: 1860)\*\*



Metrics Visualized:



\* CPU Usage

\* Memory Usage

\* Disk Utilization

\* Network Throughput

\* Filesystem Usage

\* System Load Average

\* Server Uptime



\---



\## 📡 Prometheus Metrics Collection



Prometheus continuously scrapes metrics from Node Exporter and stores them as time-series data for visualization and alerting.



\---



\## 🔐 Production Considerations



\* Containerized deployment using Docker Compose

\* Service isolation through Docker networking

\* Scalable monitoring architecture

\* Ready for AlertManager integration

\* Easy integration with cloud infrastructure



\---



\## 🚀 Future Enhancements



\* AlertManager Integration

\* Slack / Email Notifications

\* Kubernetes Monitoring

\* cAdvisor Integration

\* Loki Log Aggregation

\* Prometheus Alert Rules

\* Multi-node Monitoring



\---



\## 👩‍💻 Author



\*\*Ishika Kamble\*\*



DevOps Engineer | Docker | Linux | CI/CD | Monitoring \& Observability



\---



\## ⭐ Project Outcome



This project demonstrates:



✅ Infrastructure Monitoring

✅ Metrics Collection

✅ Observability Engineering

✅ Dockerized Deployment

✅ Production-Style Dashboarding

✅ DevOps Best Practices



