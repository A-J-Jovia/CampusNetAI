# CampusNetAI

### AI-Powered Campus Connectivity Intelligence Platform

CampusNet AI is a production-ready intelligent network analytics platform designed to monitor, analyze, predict, and optimize campus WiFi performance using Data Engineering, Machine Learning, Generative AI, and Agentic AI.

The platform transforms raw network logs into actionable insights, helping campus administrators understand network behavior, predict congestion, generate AI-powered reports, and interact with network data through natural language queries.

---

## 🚀 Features

### 📊 Executive Dashboard

* Real-time network performance overview
* KPI monitoring
* Congestion analytics
* Network health indicators
* Building-wise performance tracking

### 📈 Network Analytics

* Download speed analysis
* Latency monitoring
* User density analysis
* Event impact analytics
* Building comparison dashboard
* Interactive visualizations

### 🤖 Congestion Prediction

Machine Learning-powered congestion prediction using:

* Connected Users
* Bandwidth Usage
* Download Speed
* Upload Speed
* Latency
* Signal Strength
* Weather Conditions
* Campus Events

Prediction Classes:

* Low Congestion
* Medium Congestion
* High Congestion

### 🧠 AI Report Generator

Generates professional network reports using Large Language Models.

Reports include:

* Network Health Summary
* Key Metrics Analysis
* Potential Issues
* Risk Assessment
* Optimization Recommendations

### ⚡ Agentic AI Assistant

Natural Language to SQL Agent.

Users can ask questions such as:

* Which building has the highest latency?
* Show top 5 congested zones.
* Which event generates the most traffic?
* Which building has the highest download speed?
* Which area experiences the worst network health?

Agent Workflow:

User Question
→ SQL Generation
→ Database Query
→ Result Retrieval
→ AI Response

### 🏫 Campus Digital Twin

Visual representation of campus connectivity status.

Tracks:

* Buildings
* Network Health
* Congestion Levels
* Connectivity Status

---

## 🏗️ System Architecture

Dataset
↓
Data Cleaning & Preprocessing
↓
SQLite Database
↓
SQL Analytics
↓
ETL Pipeline
↓
PySpark Medallion Architecture
↓
Machine Learning Model
↓
Generative AI Layer
↓
Agentic AI Layer
↓
Streamlit Application

---

## 🛠️ Technologies Used

### Data Engineering

* Pandas
* NumPy
* SQLite
* PySpark

### Machine Learning

* Scikit-Learn
* Random Forest Classifier

### Generative AI

* Groq API
* Llama 3.1

### Agentic AI

* Text-to-SQL
* Database Tool Integration

### Visualization

* Plotly
* Matplotlib

### Frontend

* Streamlit

---

## 📂 Project Structure

```text
CampusNetAI/

├── app.py
├── campus_wifi.db
├── campus_wifi_cleaned.csv
├── campus_wifi_transformed.csv
├── rf_model.pkl
├── encoders.pkl
├── requirements.txt
├── assets/
├── pages/
└── README.md
```

---

## 📡 Dataset Overview

The project uses a realistic campus WiFi dataset containing:

### Buildings

* MAIN_BLOCK
* AI_BLOCK
* MECH_BLOCK
* AMENITY
* HOSTEL_BOYS
* HOSTEL_GIRLS
* MARIO
* BUS_AREA

### Network Metrics

* Connected Users
* Bandwidth Usage
* Download Speed
* Upload Speed
* Latency
* Signal Strength
* Weather Conditions
* Event Information
* Congestion Status

### Campus Events

* Thiran
* Freshwarite
* FlashMob
* Culturals
* No_Event

---

## 🧪 Machine Learning Performance

Model Used:

* Random Forest Classifier

Target Variable:

* Congestion_Status

Prediction Classes:

* Low
* Medium
* High

The model predicts network congestion levels based on real-time network conditions and usage patterns.

---

## 🎯 Key Objectives

* Monitor campus network performance
* Detect congestion patterns
* Predict future congestion
* Generate AI-powered reports
* Enable natural language analytics
* Improve network management decisions

---

## 🔮 Future Enhancements

* Real-time IoT integration
* Live network monitoring
* Mobile application
* Automated alert system
* Predictive maintenance
* Multi-campus deployment
* Cloud deployment
* Advanced AI recommendations

---

## 👨‍💻 Developed By

JOVIA A J  - CSE(AIML)

FAZMINA S  - CSE(AIML)

ADHESH V S - IT

Sri Eshwar College of Engineering

---

## ⭐ CampusNet AI

Transforming Campus Connectivity Through Data Engineering, Machine Learning, Generative AI, and Agentic Intelligence.
