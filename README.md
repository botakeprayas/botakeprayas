<!-- ============================================================
  Prayas Botake — GitHub profile README
  Search for "TODO" before committing: those are details to verify.
  ============================================================ -->

<div align="center">

# Prayas Botake

**ML & Data Engineer** · Time-Series Machine Learning · MLOps

Building sensor-data pipelines, anomaly-detection and forecasting models,<br>
and reproducible ML workflows. Growing from Machine Learning Engineer toward AI/ML Engineer.

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Prayas_Botake-4F46E5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prayas-botake-172171341)
[![GitHub](https://img.shields.io/badge/GitHub-botakeprayas-6D28D9?style=flat-square&logo=github&logoColor=white)](https://github.com/botakeprayas)
![Location](https://img.shields.io/badge/Pune,_India-1E1B4B?style=flat-square&logo=googlemaps&logoColor=A5B4FC)

</div>

---

## About

I am a Computer Engineering student (2023–2027) and a working **ML and Data Engineer**. My work centres on turning raw sensor and time-series data into reliable machine-learning systems: cleaning and storing the data, engineering features, training and evaluating models, and exposing them through APIs.

I care about reproducibility and honest evaluation, so I track experiments, version artifacts, and prefer a working baseline over an unproven complex model.

## Current Role and Engineering Interests

**Role:** ML and Data Engineer
**Direction:** Machine Learning Engineer → AI/ML Engineer

| Focus area | What it covers |
|---|---|
| **Time-series ML** | Forecasting and anomaly detection on sensor data |
| **Data engineering** | Cleaning, feature engineering, PostgreSQL and TimescaleDB storage |
| **Deep learning and NLP** | Neural networks, text classification pipelines, transformer models (learning) |
| **MLOps** | Experiment tracking, model artifacts, API serving, containerised workflows |

---

## Technical Stack

Grouped by how I use each technology: **hands-on** is regular working use; **in progress / learning** is actively being built up.

| Domain | Hands-on | In progress / learning |
|---|---|---|
| **Programming and analysis** | ![Python](https://img.shields.io/badge/Python-1E1B4B?style=flat-square&logo=python&logoColor=A5B4FC) ![SQL](https://img.shields.io/badge/SQL-1E1B4B?style=flat-square&logo=postgresql&logoColor=A5B4FC) ![NumPy](https://img.shields.io/badge/NumPy-1E1B4B?style=flat-square&logo=numpy&logoColor=A5B4FC) ![Pandas](https://img.shields.io/badge/Pandas-1E1B4B?style=flat-square&logo=pandas&logoColor=A5B4FC) ![Matplotlib](https://img.shields.io/badge/Matplotlib-1E1B4B?style=flat-square&logo=matplotlib&logoColor=A5B4FC) ![Seaborn](https://img.shields.io/badge/Seaborn-1E1B4B?style=flat-square&logoColor=A5B4FC) | n/a |
| **Machine learning** | ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1E1B4B?style=flat-square&logo=scikitlearn&logoColor=A5B4FC) Feature engineering · Model evaluation · Time-series forecasting · Anomaly detection | Advanced forecasting methods |
| **Deep learning** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-1E1B4B?style=flat-square&logo=tensorflow&logoColor=A5B4FC) ![Keras](https://img.shields.io/badge/Keras-1E1B4B?style=flat-square&logo=keras&logoColor=A5B4FC) ![PyTorch](https://img.shields.io/badge/PyTorch-1E1B4B?style=flat-square&logo=pytorch&logoColor=A5B4FC) Deep neural networks | Sequence models for sensor data |
| **NLP** | Text preprocessing · Tokenization · TF-IDF · Text classification · NLP pipelines | ![Hugging Face](https://img.shields.io/badge/Transformers-1E1B4B?style=flat-square&logo=huggingface&logoColor=A5B4FC) Transformer models |
| **Databases and data engineering** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1E1B4B?style=flat-square&logo=postgresql&logoColor=A5B4FC) ![TimescaleDB](https://img.shields.io/badge/TimescaleDB-1E1B4B?style=flat-square&logo=timescale&logoColor=A5B4FC) ![MySQL](https://img.shields.io/badge/MySQL-1E1B4B?style=flat-square&logo=mysql&logoColor=A5B4FC) Time-series data processing | n/a |
| **MLOps and deployment** | REST APIs · Experiment tracking | ![Docker](https://img.shields.io/badge/Docker-1E1B4B?style=flat-square&logo=docker&logoColor=A5B4FC) ![MLflow](https://img.shields.io/badge/MLflow-1E1B4B?style=flat-square&logo=mlflow&logoColor=A5B4FC) ![FastAPI](https://img.shields.io/badge/FastAPI-1E1B4B?style=flat-square&logo=fastapi&logoColor=A5B4FC) Model serving · Model monitoring |
| **Analytics and tools** | ![Git](https://img.shields.io/badge/Git-1E1B4B?style=flat-square&logo=git&logoColor=A5B4FC) ![GitHub](https://img.shields.io/badge/GitHub-1E1B4B?style=flat-square&logo=github&logoColor=A5B4FC) ![VS Code](https://img.shields.io/badge/VS_Code-1E1B4B?style=flat-square&logo=visualstudiocode&logoColor=A5B4FC) ![Jupyter](https://img.shields.io/badge/Jupyter-1E1B4B?style=flat-square&logo=jupyter&logoColor=A5B4FC) ![Colab](https://img.shields.io/badge/Colab-1E1B4B?style=flat-square&logo=googlecolab&logoColor=A5B4FC) ![Power BI](https://img.shields.io/badge/Power_BI-1E1B4B?style=flat-square&logo=powerbi&logoColor=A5B4FC) ![Tableau](https://img.shields.io/badge/Tableau-1E1B4B?style=flat-square&logo=tableau&logoColor=A5B4FC) | n/a |

---

## Featured Projects

### INTeLLISeNZ: Structural Health Monitoring

`Status: Active development`

A structural health monitoring system that analyses sensor data from structures such as bridges, buildings, tunnels, and retaining walls. It covers the path from raw time-series data to model output.

- Sensor time-series ingestion, cleaning, and feature engineering
- Anomaly detection and forecasting with machine-learning and deep-learning models
- Storage in PostgreSQL and TimescaleDB
- API integration and dashboard development
- Model evaluation and MLOps workflows

**Stack:** Python · Scikit-learn · TensorFlow/Keras · PostgreSQL · TimescaleDB · MLflow

<!-- TODO: Replace with the real repository URL, or delete this line if the code is private or employer-owned. -->
[Repository](https://github.com/botakeprayas/REPLACE_WITH_INTELLISENZ_REPO)

### Live Motion Sensor Classification

`Status: Working prototype`  <!-- TODO: confirm status -->

A real-time motion classifier built on an MPU6050 accelerometer and gyroscope. An Arduino streams sensor readings over serial, a Python process runs live inference, and Streamlit visualises the predicted motion.

- Arduino-based sensor data acquisition
- Live serial streaming into Python
- Machine-learning classification of motion patterns
- Streamlit interface for live visualisation

**Stack:** Arduino · Python · Scikit-learn · Streamlit

<!-- TODO: Replace with the real repository URL. -->
[Repository](https://github.com/botakeprayas/REPLACE_WITH_MOTION_CLASSIFIER_REPO)

### MLflow and Model Deployment Platform

`Status: In progress`

An ML engineering project for tracking experiments, managing model artifacts, and serving models through an API. The goal is a reproducible path from training run to deployed service.

- Experiment tracking and model artifact management with MLflow
- Model serving through FastAPI
- Containerised workflow with Docker

**Stack:** Python · MLflow · FastAPI · Docker

<!-- TODO: Replace with the real repository URL. -->
[Repository](https://github.com/botakeprayas/REPLACE_WITH_MLFLOW_DEPLOYMENT_REPO)

### Data Analytics Projects

Earlier work in SQL, Excel, and Power BI that built my foundation in data cleaning and business analysis.

| Project | Focus |
|---|---|
| [Hospital Emergency Room SQL Project](https://github.com/botakeprayas/Hospital_Emegency_room_SQL_Project) | SQL analysis of 9,216 emergency-room patient records: admissions, referrals, satisfaction, wait times |
| [E-Commerce Performance Dashboard](https://github.com/botakeprayas/E-Commerce-Performance-Dashboard) | SQL and Power BI analysis of revenue, customer behaviour, and operational efficiency |
| [E-Commerce Sales Analysis Dashboard](https://github.com/botakeprayas/E-Commerce-Sales-Analysis-Dashboard-Power-BI-) | Interactive Power BI dashboard on revenue trends, top products, and customer demographics |
| [HR Attrition and Workforce Insights](https://github.com/botakeprayas/HR-Attrition-Workforce-Insights-Dashboard) | Workforce and attrition dashboard |
| [Data Analysis Dashboard](https://github.com/botakeprayas/Data_Analysis_dashboard) | Excel dashboards covering data processing, cleaning, and analysis |

---

## Current Learning Focus

- **Production ML workflows:** reproducible training with MLflow, Docker, and FastAPI
- **Model monitoring:** detecting data drift and performance decay after deployment
- **Transformer models:** applying them to NLP tasks beyond TF-IDF baselines
- **Time-series deep learning:** stronger forecasting and anomaly-detection methods for sensor data

---

## GitHub Statistics

<div align="center">

<img width="49%" alt="Prayas Botake's GitHub statistics" src="https://github-readme-stats.vercel.app/api?username=botakeprayas&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&bg_color=0D1117&title_color=8B5CF6&icon_color=3B82F6&text_color=C9D1D9" />

<img width="100%" alt="Prayas Botake's GitHub contribution graph" src="https://github-readme-activity-graph.vercel.app/graph?username=botakeprayas&bg_color=0D1117&color=C9D1D9&line=8B5CF6&point=3B82F6&area=true&area_color=6366F1&hide_border=true" />

</div>

---

## Contact

I am glad to talk about time-series ML, sensor-data projects, MLOps, or engineering careers.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-4F46E5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prayas-botake-172171341)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-6D28D9?style=flat-square&logo=github&logoColor=white)](https://github.com/botakeprayas)

---

<div align="center">

<sub>Prayas Botake · ML and Data Engineer · Pune, India</sub>

</div>
