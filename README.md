
#  Real-Time System Monitoring using Prometheus, Node Exporter & Grafana

## Project Overview

This project demonstrates a real-time system monitoring system using **Prometheus, Node Exporter, and Grafana** on Ubuntu Linux (VirtualBox).

It helps to monitor system performance like CPU usage, memory usage, disk usage, and network activity in real time.

---

## System Architecture

```text id="r1"
                        Ubuntu System
                              ↓
                        Node Exporter
                              ↓
                        Prometheus
                              ↓
                        Grafana
                              ↓
                        User Dashboard
                        

---

## Tools Used

* Ubuntu Linux
* Node Exporter
* Prometheus
* Grafana
* VirtualBox

---

## Ports Used

| Service       | Port |
| ------------- | ---- |
| Node Exporter | 9100 |
| Prometheus    | 9090 |
| Grafana       | 3000 |

---

## Working Flow

* Ubuntu generates system metrics (CPU, RAM, Disk, Network)
* Node Exporter collects system data
* Prometheus scrapes and stores metrics
* Grafana visualizes data in dashboards

---

## Live URLs

* Node Exporter: [http://localhost:9100/metrics]
* Prometheus: [http://localhost:9090]
* Grafana: [http://localhost:3000]

---

## Screenshots

<img width="1917" height="953" alt="Grafana" src="https://github.com/user-attachments/assets/990100e5-3a0d-4904-93f1-0edc3e504e1d" />
<img width="1920" height="964" alt="prometheus" src="https://github.com/user-attachments/assets/308ceb9b-3342-4927-b6fb-e65f3d5e6e75" />
<img width="1920" height="940" alt="node-exporter" src="https://github.com/user-attachments/assets/309c2563-9ac7-495b-a1a2-2272f9ef3225" />

## DevOps Importance

* Real-time system monitoring
* Server performance tracking
* Early problem detection
* Alert system support
* Infrastructure visibility

---

## Alerting Feature

Prometheus can generate alerts when:

* CPU usage is high (>80%)
* Memory usage is high
* Server goes down
* Disk is full

---

## Conclusion

Node Exporter collects system metrics, Prometheus stores them, and Grafana visualizes them in dashboards.

This system is widely used in DevOps environments for real-time monitoring and performance analysis.

---

## How to Use

1. Install tools
2. Start Node Exporter
3. Run Prometheus
4. Open Grafana
5. Import dashboard
6. View live monitoring

---
