# 🔍 Monitoring System with Grafana, Prometheus, and Node Exporter

This project implements a complete, open-source monitoring and alerting system using **Grafana**, **Prometheus**, and **Node Exporter** on a Linux environment (tested on Kali Linux with Apple Silicon). It provides real-time system metrics visualization, proactive alerting, and infrastructure observability.

---

## 📌 Project Overview

The goal of this project is to build a lightweight, extensible, and user-friendly monitoring stack for system administrators and cybersecurity professionals. It allows users to:

- Collect and store system metrics (CPU, RAM, disk I/O, etc.)
- Visualize metrics through interactive Grafana dashboards
- Configure alerts for proactive monitoring and response

---

## ⚙️ Components Used

| Tool          | Purpose                                   |
|---------------|-------------------------------------------|
| **Prometheus**| Metric collection and time-series storage |
| **Grafana**   | Dashboard visualization and alerting      |
| **Node Exporter** | Exposes system metrics to Prometheus |

---

## 📁 Project Structure

├── README.md
├── Grafana.pdf     # Full installation & configuration guide


---

## 🛠️ Setup Instructions

Detailed instructions for installation and configuration can be found in [`Grafana.pdf`](./Grafana.pdf). Key steps include:

### 🔹 Grafana Setup
- Install Grafana using APT
- Enable and start Grafana service
- Access via `http://localhost:3000`
- Default credentials: `admin/admin`

### 🔹 Prometheus Setup
- Download and configure Prometheus
- Define scrape targets for Node Exporter
- Enable and start the Prometheus service
- Access via `http://localhost:9090`

### 🔹 Node Exporter Integration
- Install Node Exporter and create a systemd service
- Configure Prometheus to scrape Node Exporter at `localhost:9100`
- Start and verify metrics collection

---

## 📊 Dashboard & Alerting

- Add Prometheus as a data source in Grafana
- Import dashboards for real-time visualization
- Configure alert rules in Prometheus
- Integrate notification channels (Telegram, email, etc.)

---

## ✅ Features Implemented

- Real-time system metrics collection
- Custom dashboards for Linux performance
- Alert rule configuration for CPU, memory, and more
- Multiple notification channels
- Systemd-based service management

---

## 🚀 Skills Demonstrated

- Linux system administration
- Metric-based monitoring and analysis
- Alert configuration and optimization
- Open-source tool integration (Grafana + Prometheus)
- Network and performance troubleshooting

