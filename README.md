# PulseGuard

Real-time incident detection and intelligent alerting system.

## Problem
Companies lose revenue due to delayed detection of system failures.

## Solution
PulseGuard ingests logs and metrics in real-time, detects anomalies using statistical and ML-based approaches, and triggers instant alerts.

## Architecture
- FastAPI ingestion layer
- Redis streaming pipeline
- Python processing workers
- Anomaly detection engine
- PostgreSQL storage
- Web dashboard

## Features
- Real-time log ingestion
- Anomaly detection (Z-score / ML)
- Multi-channel alerts (Discord, Slack, Email)
- Incident dashboard
- Simulated load generator

## Tech Stack
Python, FastAPI, Redis, PostgreSQL, Docker

## Getting Started
docker-compose up --build
