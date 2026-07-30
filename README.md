# KubeHeal
Event Driven Incident Response System - Kubernetes &amp; Prometheus


# Event Driven Auto Remediation System

## 📘 Project Overview
This project implements an automated incident response system for Kubernetes using event-driven architecture. The system monitors applications, detects failures, and performs auto-remediation without human intervention.

## 🎯 Objectives
- Real-time monitoring of Kubernetes workloads  
- Automated detection of failures  
- Self-healing through remediation engine  
- Reduce manual DevOps effort  

## 🧱 Architecture
Prometheus → Alertmanager → Webhook → Remediation Engine → Kubernetes Action
<img width="428" height="336" alt="image" src="https://github.com/user-attachments/assets/bf3e800d-7e72-416f-ac4d-4d3bf4dc168f" />


## 🛠 Technologies
- Kubernetes (Minikube)
- Prometheus & Alertmanager
- Python Flask
- Docker
- kubectl

## 👥 Team Roles
- Member 1: Prometheus & Grafana Setup
- Member 2: Alert Rules Configuration
- Member 3: Remediation Scripts & GitHub

## 📂 Structure
- devops-incident-response/
- ├── kubernetes/
- │   ├── alert-rules.yaml              # Alert detection rules
- │   └── alertmanager-config.yaml      # Alert routing config
- ├── scripts/
- │   └── remediation-scripts.sh        # Auto-remediation scripts
- ├── monitoring/
- │   └── prometheus-values.yaml        # Prometheus config
- ├── docs/
- │   ├── SETUP.md                      # Installation guide
- │   ├── DEMO_INSTRUCTIONS.md          # How to demo
- │   └── TEAM_WORKFLOW.md              # Git workflow guide
- ├── README.md                         # This file
- └── .gitignore                        # Files to ignore 

## 🚀 How to Run
1. Start Minikube  
2. Deploy sample app  
3. Install Prometheus  
4. Configure alerts

## Screenshots
1. Grafana Dashboard
<img width="1919" height="866" alt="Screenshot 2026-04-23 114649" src="https://github.com/user-attachments/assets/84610211-af9d-40a7-978d-60f1a99d903c" />

2. Remediation engine running
<img width="1303" height="494" alt="Screenshot 2026-04-23 135947" src="https://github.com/user-attachments/assets/e1af4ac8-7575-4e13-8473-42af5bbbd7c8" />

3. Prometheus showing Alerts
<img width="1903" height="607" alt="Screenshot 2026-05-01 105221" src="https://github.com/user-attachments/assets/c26f6360-6ce9-4343-aa45-ebecb4ea42d4" />

4. Alert Triggered
<img width="1852" height="373" alt="Screenshot 2026-05-01 105706" src="https://github.com/user-attachments/assets/adada086-fd85-41fe-b8f9-360c3a400b12" />

5. Alert Firing
<img width="1854" height="340" alt="Screenshot 2026-05-01 133942" src="https://github.com/user-attachments/assets/cf3fe7fd-f14e-43ce-abc6-0941bc92f1b3" />

6. Remediation engine restarting pod
<img width="1405" height="187" alt="Screenshot 2026-05-01 133932" src="https://github.com/user-attachments/assets/60d3471f-dab5-45b1-998d-af5fcac0c132" />



## 📌 Future Scope
- Email/SMS notifications  
- AI based decision engine  
- Multi cluster support  
