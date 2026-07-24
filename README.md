# 🌱 GreenIntel — Smart Farming & Crop Prediction System

&lt;div align="center"&gt;

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.x-000000?logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-F7931E?logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Accuracy](https://img.shields.io/badge/Model%20Accuracy-99.24%25-brightgreen)

**AI-powered crop recommendation system that helps farmers make data-driven decisions using Machine Learning.**

[🚀 Live Demo](#) • [📊 Screenshots](#-system-screenshots) • [📖 Report Bug](https://github.com/YOUR_USERNAME/GreenIntel-Smart-Farming/issues) • [✨ Request Feature](https://github.com/YOUR_USERNAME/GreenIntel-Smart-Farming/issues)

&lt;/div&gt;

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [ML Model Performance](#-ml-model-performance)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Supported Crops](#-supported-crops)
- [Screenshots](#-system-screenshots)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 Overview

Agriculture is the backbone of the economy, yet farmers frequently struggle with **crop selection** based on soil and climate conditions. Choosing the wrong crop leads to reduced yield, wasted resources, and financial loss.

**GreenIntel** solves this problem using a **Random Forest Machine Learning model** trained on agricultural data. By analyzing 7 key parameters — Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall — the system predicts the **most suitable crop** with **99.24% accuracy**.

&gt; 💡 *Empowering farmers with AI-driven insights for smarter, more productive farming.*

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🤖 **AI Crop Prediction** | Predicts the best crop based on soil & environmental data |
| 📊 **Data Analysis** | Visualizes soil and environmental parameter distributions |
| 🏆 **Model Comparison** | Benchmarks 5 ML algorithms to find the best performer |
| 🌐 **Web Interface** | Clean, responsive Flask app with real-time predictions |
| 📈 **Dashboard** | Interactive charts for performance visualization |
| ⚡ **Real-Time** | Instant predictions with no latency |

---

## 🛠️ Tech Stack

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)

### Backend & ML
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?logo=python&logoColor=white)

---

## 🧠 ML Model Performance

The project evaluates **5 supervised learning algorithms** on the crop recommendation dataset (660 samples, 22 crop classes):

| Rank | Algorithm | Accuracy |
|:----:|-----------|----------:|
| 🥉 | Logistic Regression | 95.15% |
| 🥈 | SVM | 96.36% |
| 🥉 | KNN | 97.72% |
| 🥈 | Decision Tree | 98.63% |
| 🥇 | **Random Forest** | **99.24%** ✅ |

**Cross-Validation Accuracy:** `99.40%`

### Classification Report (Random Forest)

| Crop | Precision | Recall | F1-Score | Support |
|------|:---------:|:------:|:--------:|:-------:|
| Apple | 1.00 | 1.00 | 1.00 | 34 |
| Banana | 1.00 | 1.00 | 1.00 | 26 |
| Blackgram | 1.00 | 1.00 | 1.00 | 26 |
| Chickpea | 1.00 | 1.00 | 1.00 | 34 |
| Coconut | 1.00 | 1.00 | 1.00 | 33 |
| Coffee | 1.00 | 1.00 | 1.00 | 30 |
| Cotton | 1.00 | 1.00 | 1.00 | 28 |
| Grapes | 1.00 | 1.00 | 1.00 | 23 |
| **Jute** | **0.87** | **1.00** | **0.93** | **34** |
| Kidneybeans | 1.00 | 1.00 | 1.00 | 36 |
| Lentil | 1.00 | 1.00 | 1.00 | 22 |
| Maize | 1.00 | 1.00 | 1.00 | 26 |
| Mango | 1.00 | 1.00 | 1.00 | 32 |
| Mothbeans | 1.00 | 1.00 | 1.00 | 34 |
| Mungbean | 1.00 | 1.00 | 1.00 | 30 |
| Muskmelon | 1.00 | 1.00 | 1.00 | 24 |
| Orange | 1.00 | 1.00 | 1.00 | 25 |
| Papaya | 1.00 | 1.00 | 1.00 | 37 |
| Pigeonpeas | 1.00 | 1.00 | 1.00 | 37 |
| Pomegranate | 1.00 | 1.00 | 1.00 | 38 |
| **Rice** | **1.00** | **0.82** | **0.90** | **28** |
| Watermelon | 1.00 | 1.00 | 1.00 | 23 |

**Overall:** `Accuracy = 0.99` | `Macro Avg F1 = 0.99` | `Weighted Avg F1 = 0.99`

---

## 🚀 Installation

### Prerequisites
- Python 3.9+
- pip

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/GreenIntel-Smart-Farming.git
cd GreenIntel-Smart-Farming
