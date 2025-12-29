# Annomatrix

# 🔍 Annomatrix – Real-Time Anomaly Detection & Monitoring System

Annomatrix is an intelligent real-time anomaly detection system designed to monitor service performance metrics such as response time, errors, and usage patterns. The system uses machine learning (Isolation Forest, Z-Score, and Rolling Statistics) to detect anomalies and sends real-time alerts to Microsoft Teams. It supports PostgreSQL for data storage and integrates seamlessly with Metabase for live visualization.

---

## 🚀 Features

- ✅ Real-time ingestion and monitoring of service metrics.
- 🧠 Hybrid anomaly detection using:
  - Z-Score Method
  - Rolling Window Statistics
  - Isolation Forest (Sklearn)
- 📊 Live dashboards with Metabase (auto-updating tables and charts).
- 📥 PostgreSQL for data storage.
- 📩 Microsoft Teams integration for alerts.
- ⚙️ Fully modular, extendable, and testable Python architecture.

---

## 🏗️ Tech Stack

- **Python** (Pandas, NumPy, SQLAlchemy, Sklearn, Requests)
- **PostgreSQL** for real-time data ingestion and storage
- **Metabase** for real-time dashboard visualization
- **Microsoft Teams Webhook API** for instant alerts
- **Jupyter / VS Code** as the development environment

---

## 📸 Sample Screenshot

> Insert a live dashboard image or sample output if available.
> 


---

## 🧪 How It Works

1. PostgreSQL receives real-time metrics via data insertion scripts.
2. Python script continuously monitors and processes new data.
3. Anomaly detection logic is applied.
4. Detected anomalies trigger alert messages to Microsoft Teams.
5. Metabase dashboard auto-refreshes to show latest updates.

---

