# 🌱 Community Project Tracker

A full-stack project tracking and analytics application running on Google Cloud Run, backed by Firestore and BigQuery.

### 🚀 Live Demo
[![Open Live Application](https://img.shields.io/badge/Launch-Live%20App-brightgreen?style=for-the-badge&logo=googlecloud)](https://community-project-tracker-189078890713.europe-west1.run.app/)

Click the badge above or navigate to:
**[https://community-project-tracker-189078890713.europe-west1.run.app/](https://community-project-tracker-189078890713.europe-west1.run.app/)**

---

## 🛠️ Architecture
- **Compute**: Google Cloud Run (Containerized Flask App)
- **Database**: Cloud Firestore (Native Mode for active operational data)
- **Data Warehouse**: BigQuery (`community_analytics.participants` for metrics)
- **CI/CD**: GitHub Actions (Automatic container build & deployment on push)
