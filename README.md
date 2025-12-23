# Dexter AI – Phase 1

Dexter AI is a hybrid network security system that combines
signature-based intrusion detection systems (IDS) with
machine learning–based anomaly detection.

This repository contains Phase 1 (MVP) of the project,
focused on network-level threat detection.

---

## Phase 1 Goal (MVP)

Build a hybrid network defense module that:

- Detects known attacks using signature-based IDS (Suricata)
- Detects unknown / zero-day behaviors using ML-based anomaly detection
- Collects, processes and analyzes network traffic in a simulated environment
- Produces structured outputs for monitoring and future automation

---

## Core Components

### Infrastructure Simulation
- Docker-based enterprise network simulation
- Internal and external network segments
- User nodes, servers and attacker simulation

### IDS Layer
- Suricata for signature-based detection
- Alert and traffic log generation

### Data Pipeline
- Log collection in JSON format
- Feature extraction and preprocessing
- Dataset generation for ML training

### Machine Learning
- Anomaly detection models
- Normal vs suspicious traffic learning
- Risk scoring (Phase 1 prototype)

---

## Technologies

- Python
- Docker & Docker Compose
- Suricata IDS
- Pandas, NumPy
- Scikit-learn

---

## Repository Structure

