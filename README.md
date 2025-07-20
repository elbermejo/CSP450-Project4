# CSP450 Project 4: Transactional Machine Learning (TML), Cisco Packet Tracer (CPT) and Artificial Intelligence (PrivateGPT): Cyberthreat Detection, AI and Real-Time Network Monitoring with Kafka Cloud, Python, Docker, MariaDB, TMUX and Real-Time Dashboard Running in Linux

## Overview

This project demonstrates a real-time network monitoring and cyberthreat detection solution using Transactional Machine Learning (TML), Cisco Packet Tracer (CPT), Artificial Intelligence (PrivateGPT), Kafka Cloud, Docker, and a live visualization dashboard.  
The system detects and visualizes network anomalies, including which host machines are being hacked, in real-time—simulating an enterprise environment.

## Objectives

- Detect and visualize in real-time which host machines have been hacked or taken offline.
- Integrate multiple technologies: Kafka Cloud, Docker, Python, TML, PrivateGPT, IoT, and real-time dashboards.
- Enable real-time, data-driven decision making through a browser-based dashboard.
- Provide evidence/screenshots answering the 16 required analytical questions.

## Technologies Used

- **Docker** (container orchestration)
- **Kafka Cloud (Confluent Cloud)** (real-time data streaming)
- **Python** (data processing and machine learning)
- **PrivateGPT** (AI and natural language processing)
- **Qdrant** (vector database, if used with PrivateGPT)
- **Cisco Packet Tracer** (network simulation)
- **TMUX** (process/session management)
- **Linux (Ubuntu)** (host OS)

## Prerequisites

- Docker installed on your system.
- Credentials for Confluent Cloud Kafka cluster.
- Ports 6333, 8001, and 9000 free on your system.

---

## How to Run

### 1. Pull Required Docker Images

```bash
docker pull qdrant/qdrant
docker pull maadsdocker/tml-privategpt-no-gpu-amd64:latest
docker pull maadsdocker/tml-cisco-network-cyberthreats-privategpt-amd64:latest
