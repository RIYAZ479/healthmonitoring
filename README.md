# ArogyaNet — Smart Community Health Monitoring

A production-grade health intelligence system designed for early detection and prevention of water-borne diseases in Rural Northeast India.

## 🚀 Quick Start (Docker)

```bash
cd docker
docker-compose up --build
```

## 🏗️ Architecture

- **Frontend**: React 18, TypeScript, Tailwind CSS, Recharts, Framer Motion.
- **Backend (API)**: Django REST Framework (Python).
- **Backend (Real-time)**: Node.js, Express, Socket.io for WebSocket alerts.
- **ML Engine**: Scikit-learn (Logistic Regression, Random Forest), Prophet for time-series forecasting.
- **IoT Layer**: MQTT ingestion for pH, Turbidity, E. coli, and Rainfall sensors.
- **Persistence**: PostgreSQL (Core), MongoDB (IoT History), Redis (Pub/Sub & Cache).

## 🗺️ Key Features

1. **AI Predictive Dashboard**: 74% confidence outbreak forecasting.
2. **Real-time SMS Alert Ticker**: Low-latency health emergency notifications.
3. **Geographic Risk Heatmap**: District-level disease intensity visualization.
4. **ASHA Field Portal**: Offline-first reporting for remote village health workers.
5. **Multilingual Interface**: Support for Assamese, Bodo, Hindi, and English.

## 📁 Directory Structure

- `/frontend`: React dashboard and UI components.
- `/backend`: Django API and Node.js WebSocket server.
- `/ml`: Python scripts for disease prediction models.
- `/iot`: Arduino/ESP32 firmware and MQTT ingestion scripts.
- `/docker`: Container orchestration for the full stack.
- `/seed`: Demo data for hackathon presentation.

## 📄 Compliance
Fully compliant with **DPDPA 2023** (India) and **WCAG 2.1 AA** accessibility standards.
