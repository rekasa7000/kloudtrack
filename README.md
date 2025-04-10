# Kloudtrack

**KloudTrack System** is a weather station management platform built to monitor, control, and maintain environmental IoT devices in real-time. It supports multi-level user access, real-time data visualization, two-way device communication, and historical data analysis—all designed for organizations and individuals who rely on accurate, localized weather insights.

---

## 🚀 Features

### Super Admin Dashboard
- Full system oversight and access control
- Manage all stations and users
- Trigger global firmware updates
- Monitor server health and logs

### Admin Dashboard
- Manage organization-owned weather stations
- Real-time station monitoring and sensor data
- Station control (reboot, reset)
- Organization user management
- Custom alerts & notifications

### User Dashboard
- Live and historical weather data
- Email alerts and notifications
- Data download options (CSV/JSON)

---

## Station Capabilities

- Real-time data reporting (1-minute interval)
- Two-way control using MQTT
- Firmware versioning and remote updates
- OTA (Over-the-Air) device management
  
---

## Tech Stack

### Frontend
- Vite + React + TypeScript
- Tailwind CSS for styling

### Backend
- Node.js + Express + Python + FastAPI
- WebSockets for real-time updates
- MQTT for station communication
- REST API for client interactions
- PostgreSQL 
- Data-analysis

### Infrastructure
- Docker-ready setup
- VPS-based deployment (cloud-native options in future)
- Logging and basic CloudWatch monitoring

---

