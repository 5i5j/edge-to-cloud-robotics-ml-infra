# Edge-to-Cloud Robotics: ML Infrastructure

## 🚀 Overview
This project defines the centralized infrastructure hosted on the **ThinkStation P620**. It serves as the data hub for the entire robotics pipeline, handling data ingestion from edge nodes (e.g., Raspberry Pi) and providing storage for ML model training.

## 🔗 Architecture
- **Object Storage**: MinIO (S3-compatible) for ROS 2 bag files/MCAP.
- **Database**: PostgreSQL for metadata and experiment tracking.
- **MLOps**: Integrated with Databricks/Spark-based lakehouse architectures.

## 🛠️ Usage
To spin up the infrastructure:
```bash
docker compose up -d
