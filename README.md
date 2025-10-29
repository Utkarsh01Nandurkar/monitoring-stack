# Monitoring Stack – Prometheus + Grafana + Node Exporter

This project provides a lightweight **observability stack** using Prometheus, Grafana, and Alertmanager to monitor EC2 or Kubernetes environments.

## 🚀 Features
- Collects system and container metrics with Node Exporter.
- Visualizes metrics and dashboards using Grafana.
- Sends Slack alerts for CPU, memory, and uptime anomalies.
- Fully containerized with Docker Compose.

## 🧩 Tech Stack
- Prometheus  
- Grafana  
- Node Exporter  
- Alertmanager  
- Slack Webhook Integration  

## ▶️ Quick Start
```bash
git clone https://github.com/Utkarsh01Nandurkar/monitoring-stack.git
cd monitoring-stack
docker-compose up -d
