# 🐧 Linux Infrastructure Monitoring Stack

Built a production-grade monitoring pipeline on *Ubuntu 22.04* using the Prometheus-Grafana stack. This project replaces basic tools like htop with a scalable, historical data-driven observability system.

**## 🏗️ Architecture**
*[System Metrics]* ➔ *[Node Exporter:9100]* ➔ *[Prometheus:9090]* ➔ *[Grafana:3000]*

## 🚀 Features Implemented
- ✅ *Node Exporter*: Deployed to collect real-time hardware and OS metrics.
- ✅ *Prometheus*: Configured as a Time-Series Database (TSDB) with custom scrape intervals.
- ✅ *Grafana*: Built interactive dashboards for visualizing CPU, Memory, Disk, and Network health.
- ✅ *Systemd Automation*: Created custom .service files to ensure services survive reboots.
- ✅ *Troubleshooting*: Resolved IPv4/IPv6 port binding issues and analyzed logs using journalctl.

## 🛠️ Tech Stack
- *OS*: Ubuntu 22.04 LTS
- *Tools*: Prometheus, Grafana, Node Exporter
- *Monitoring*: CPU, Memory, Disk usage, and Network I/O.

---
### How to Run:
1. Start Node Exporter service: sudo systemctl start node_exporter
2. Run Prometheus: sudo systemctl start prometheus
3. Access Grafana at http://localhost:3000

<img width="947" height="599" alt="image" src="https://github.com/user-attachments/assets/ffce050a-fb5e-4cf5-b79c-606ba62e94b1" />
<img width="930" height="570" alt="image" src="https://github.com/user-attachments/assets/1a579e7f-66ef-4f28-b3f2-7e51973ab147" />
<img width="737" height="453" alt="image" src="https://github.com/user-attachments/assets/be28408e-00ff-46ab-9ab0-e96fb773dc7b" />
<img width="754" height="463" alt="image" src="https://github.com/user-attachments/assets/11a0328d-6018-461b-bd53-aae3ea5520ca" />
<img width="742" height="444" alt="image" src="https://github.com/user-attachments/assets/d4486970-4bc2-42d2-8ebf-e6c5e2b17365" />


