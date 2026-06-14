# Real-Time System Monitoring using Prometheus, Node Exporter & Grafana

## Project Overview

This project demonstrates a real-time system monitoring solution using Prometheus, Node Exporter, and Grafana on Ubuntu Linux running inside VirtualBox.

It helps monitor system performance such as CPU usage, memory usage, disk usage, and network activity in real time.

## System Architecture

```text
Ubuntu System
      ↓
Node Exporter
      ↓
Prometheus
      ↓
Grafana
      ↓
User Dashboard
```

### Architecture Description

* Ubuntu generates system metrics.
* Node Exporter collects system metrics.
* Prometheus scrapes and stores the metrics.
* Grafana visualizes the metrics through dashboards and graphs.
* Users can monitor system performance in real time.

## Tools Used

* Ubuntu Linux
* Node Exporter
* Prometheus
* Grafana
* VirtualBox

## Ports Used

| Service       | Port |
| ------------- | ---- |
| Node Exporter | 9100 |
| Prometheus    | 9090 |
| Grafana       | 3000 |

## Working Flow

1. Ubuntu generates system metrics such as CPU, RAM, Disk, and Network usage.
2. Node Exporter collects these metrics from the operating system.
3. Prometheus scrapes and stores the collected metrics.
4. Grafana retrieves the metrics from Prometheus.
5. Grafana displays the data using dashboards and graphs.

## Live URLs

* Node Exporter: http://localhost:9100/metrics
* Prometheus: http://localhost:9090
* Grafana: http://localhost:3000

## Screenshots

### Grafana Dashboard

<img width="1917" height="953" alt="Grafana" src="https://github.com/user-attachments/assets/990100e5-3a0d-4904-93f1-0edc3e504e1d" />

### Prometheus Dashboard

<img width="1920" height="964" alt="Prometheus" src="https://github.com/user-attachments/assets/308ceb9b-3342-4927-b6fb-e65f3d5e6e75" />

### Node Exporter Metrics

<img width="1920" height="940" alt="Node Exporter" src="https://github.com/user-attachments/assets/309c2563-9ac7-495b-a1a2-2272f9ef3225" />

## DevOps Importance

* Real-time system monitoring
* Server performance tracking
* Early problem detection
* Alert system support
* Infrastructure visibility
* Performance analysis
* Resource utilization tracking

## Alerting Feature

Prometheus can generate alerts when:

* CPU usage exceeds a defined threshold
* Memory usage becomes too high
* A server becomes unavailable
* Disk usage reaches a critical level

These alerts help administrators detect and resolve issues before they affect users.

## Conclusion

Node Exporter collects system metrics from Ubuntu Linux.

Prometheus stores and manages the collected metrics.

Grafana visualizes the metrics through dashboards and graphs.

Together, these tools provide a complete real-time monitoring solution widely used in DevOps and production environments.

## How to Use

1. Install Node Exporter.
2. Install and configure Prometheus.
3. Configure Prometheus to scrape Node Exporter metrics.
4. Install Grafana.
5. Add Prometheus as a Grafana data source.
6. Import or create a dashboard.
7. Monitor system performance in real time.
