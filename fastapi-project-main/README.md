# 🚗 Car Price Prediction API

This project is a **Machine Learning-powered web API** developed using **FastAPI**, a modern, high-performance Python framework for building RESTful services.  
FastAPI provides automatic data validation, type-hint support, and a built-in interactive API documentation (Swagger UI), making it ideal for deploying machine learning models efficiently and at scale.

---

## 🧠 Project Overview

The **Car Price Prediction API** predicts the **selling price of used cars** based on multiple input features such as brand, manufacturing year, mileage, fuel type, and transmission.  
The model is trained on a curated dataset using regression techniques, containerized with Docker, and equipped with caching, authentication, and monitoring features for production readiness.

---

## 📦 Project Features

- 🔐 **Authentication:** JWT-based token authentication and API key validation  
- 🧮 **Model Prediction:** Pretrained ML model predicts car prices via REST endpoints  
- ⚡ **Redis Caching:** Speeds up responses by avoiding redundant model computations  
- 📊 **Monitoring Ready:** Integrated **Prometheus metrics** and **Grafana dashboards** for observability  
- 🐳 **Dockerized Setup:** Simplified local development and deployment using Docker Compose  
- ☁️ **Cloud Deployment:** Easily deployable on **Render** using the included `render.yaml`  

---

## 🧰 Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Language & Framework** | 🐍 Python, ⚡ FastAPI |
| **Machine Learning** | 🧠 Scikit-learn, pandas, NumPy |
| **Data Storage** | 🗄️ CSV, Redis (for caching) |
| **Containerization** | 🐳 Docker, Docker Compose |
| **Monitoring & Metrics** | 📈 Prometheus, Grafana |
| **Cloud Deployment** | ☁️ Render |

---
## 🧠 Model Input Variables

The prediction model expects the following input features:

| Feature           | Description                          | Example         |
|------------------|--------------------------------------|-----------------|
| `company`         | Brand of the car                     | `"Maruti"`      |
| `year`            | Year of manufacturing                | `2015`          |
| `owner`           | Number of previous owners            | `"Second"`      |
| `fuel`            | Fuel type                            | `"Petrol"`      |
| `seller_type`     | Individual or Dealer                 | `"Individual"`  |
| `transmission`    | Transmission type                    | `"Automatic"`   |
| `km_driven`       | Kilometers driven                    | `200000`        |
| `mileage_mpg`     | Mileage in miles per gallon          | `55`            |
| `engine_cc`       | Engine capacity in cc                | `1250`          |
| `max_power_bhp`   | Maximum power in BHP                 | `80`            |
| `torque_nm`       | Torque in Newton meters              | `200`           |
| `seats`           | Number of seats                      | `5`             |

---

## 🚀 Getting Started (Local)

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/Software-Engineering-Projects.git
cd fastapi-project-main
```

### 2. Set Environment Variables

```bash
API_KEY=demo-key
JWT_SECRET_KEY=your-secret
REDIS_URL=redis://localhost:6379
```

### 3. Build and Run via Docker

```bash
docker-compose up --build
```

### 4. Access Interfaces

- FastAPI Docs: http://localhost:8000/docs → FastAPI’s interactive Swagger UI
- FastAPI Metrics: http://localhost:8000/metrics → Prometheus endpoint for monitoring
- Prometheus UI: http://localhost:9090 → Prometheus dashboard
- Grafana UI: http://localhost:3000 → Grafana monitoring UI

---

## 🚀 Deployment on Render
1.	Push your project to GitHub
2.	Add the included render.yaml file to the root of your repo
3.	Create a new Web Service on Render
4.	Add environment variables from the local setup
5.	Deploy 🚀

---
