# Real-Time Network Intrusion Detection & Prevention System (NIDPS)

This project is a lightweight, scalable, and real-time network intrusion detection and prevention system designed for personal and small-scale networks. It combines packet sniffing, signature-based detection, and automated responses to mitigate threats in real time.

## Features

- Real-time packet sniffing using Scapy
- Signature-based threat detection (e.g., Nmap scan, brute-force)
- Automatic blocking using firewall rules (e.g., iptables)
- Real-time alerts via console or email
- Secure logging and threat history
- Optional dashboard (Flask/FastAPI)
- Lightweight and scalable architecture

## Architecture (Coming Soon)

## Requirements

- Python 3.8+
- Scapy
- Admin/root privileges (for packet capture and blocking)
- (Optional) Flask/FastAPI for dashboard
- (Optional) Scikit-learn for anomaly detection

## Setup

```bash
git clone https://github.com/your-username/real-time-nidps.git
cd real-time-nidps
pip install -r requirements.txt
