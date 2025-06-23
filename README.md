#  Monitoring System with Grafana, Prometheus, and Node Exporter

This project implements a complete, open-source monitoring and alerting system using **Grafana**, **Prometheus**, and **Node Exporter** on a Linux environment (tested on Kali Linux with Apple Silicon). It provides real-time system metrics visualization, proactive alerting, and infrastructure observability.

---

## Project Overview

The goal of this project is to build a lightweight, extensible, and user-friendly monitoring stack for system administrators and cybersecurity professionals. It allows users to:

- Collect and store system metrics (CPU, RAM, disk I/O, etc.)
- Visualize metrics through interactive Grafana dashboards
- Configure alerts for proactive monitoring and response

---

## Components Used

| Tool          | Purpose                                   |
|---------------|-------------------------------------------|
| **Prometheus**| Metric collection and time-series storage |
| **Grafana**   | Dashboard visualization and alerting      |
| **Node Exporter** | Exposes system metrics to Prometheus |

---

## Project Structure

├── README.md
├── Grafana.pdf     # Full installation & configuration guide


---

##  Setup Instructions

Detailed instructions for installation and configuration can be found in [`Grafana (Full_Installation).pdf`](./Grafana (Full_Installation).pdf). Key steps include:

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

<img width="581" alt="Screenshot 2025-06-23 at 7 37 36 PM" src="https://github.com/user-attachments/assets/9be292ff-d269-4e67-96da-6d48a1d38cb4" />


  

### 🔹 Node Exporter Integration
- Install Node Exporter and create a systemd service
- Configure Prometheus to scrape Node Exporter at `localhost:9100`
- Start and verify metrics collection

---

## 📊 Dashboard & Alerting

![Grafana Dashboard] <img width="1436" alt="Grafana Dashboard Example" src="https://github.com/user-attachments/assets/4f1fd5fe-be8f-42c9-b919-7914d17ea2ef" />



- Add Prometheus as a data source in Grafana
- Import dashboards for real-time visualization
- Configure alert rules in Prometheus
- Integrate notification channels (Telegram, email, etc.)

---

##  Features Implemented

- Real-time system metrics collection
<img width="1431" alt="Chart_1" src="https://github.com/user-attachments/assets/69e85976-4040-4088-b434-74b3f77ecf26" />

  
- Custom dashboards and can set time ranges for Linux performance
<img width="655" alt="Time_Ranges" src="https://github.com/user-attachments/assets/c19af875-b835-436c-be37-3fc1e6fe4a2d" />

  

  
- Alert rule configuration for CPU, memory, and more
- Multiple notification channels
- Systemd-based service management
<img width="1416" alt="Chart_2" src="https://github.com/user-attachments/assets/90d89925-ff06-463e-bb6d-4f6baf981ab0" />

  

---

##  Skills Demonstrated

- Linux system administration
- Metric-based monitoring and analysis
- Alert configuration and optimization
- Open-source tool integration (Grafana + Prometheus)
- Network and performance troubleshooting

