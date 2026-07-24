# 🌱 GreenIntel — Smart Farming & Crop Prediction System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.x-black?logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-99.24%25-brightgreen)

**AI-powered crop recommendation system that helps farmers make data-driven decisions using Machine Learning.**

[🚀 Live Demo](#) • [📊 Screenshots](#-system-screenshots) • [📖 Report Bug](#) • [✨ Request Feature](#)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#️-tech-stack)
- [ML Model Performance](#-ml-model-performance)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Supported Crops](#-supported-crops)
- [Screenshots](#-system-screenshots)
- [Roadmap](#️-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-author)

---

## 🎯 Overview

Agriculture is the backbone of the economy, yet farmers frequently struggle with crop selection based on soil and climate conditions. Choosing the wrong crop leads to reduced yield, wasted resources, and financial loss.

**GreenIntel** solves this problem using a **Random Forest Machine Learning model** trained on agricultural data. By analyzing 7 key parameters — Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall — the system predicts the most suitable crop with **99.24% accuracy**.

> 💡 Empowering farmers with AI-driven insights for smarter, more productive farming.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🤖 **AI Crop Prediction** | Predicts the best crop based on soil & environmental data |
| 📊 **Data Analysis** | Visualizes soil and environmental parameter distributions |
| 🏆 **Model Comparison** | Benchmarks 5 ML algorithms to find the best performer |
| 🌐 **Web Interface** | Clean, responsive Flask app with real-time predictions |
| 📈 **Dashboard** | Interactive charts for performance visualization |
| ⚡ **Real-Time** | Instant predictions with no latency |

---

## 🛠️ Tech Stack

**Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)

**Backend & ML**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB)

---

## 🧠 ML Model Performance

The project evaluates 5 supervised learning algorithms on the crop recommendation dataset (660 samples, 22 crop classes):

| Rank | Algorithm | Accuracy |
|---|---|---|
| 🥉 | Logistic Regression | 95.15% |
| 🥈 | SVM | 96.36% |
| 🥉 | KNN | 97.72% |
| 🥈 | Decision Tree | 98.63% |
| 🥇 | **Random Forest** | **99.24%** ✅ |

**Cross-Validation Accuracy:** 99.40%

### Classification Report (Random Forest)

| Crop | Precision | Recall | F1-Score | Support |
|---|---|---|---|---|
| Apple | 1.00 | 1.00 | 1.00 | 34 |
| Banana | 1.00 | 1.00 | 1.00 | 26 |
| Blackgram | 1.00 | 1.00 | 1.00 | 26 |
| Chickpea | 1.00 | 1.00 | 1.00 | 34 |
| Coconut | 1.00 | 1.00 | 1.00 | 33 |
| Coffee | 1.00 | 1.00 | 1.00 | 30 |
| Cotton | 1.00 | 1.00 | 1.00 | 28 |
| Grapes | 1.00 | 1.00 | 1.00 | 23 |
| Jute | 0.87 | 1.00 | 0.93 | 34 |
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
| Rice | 1.00 | 0.82 | 0.90 | 28 |
| Watermelon | 1.00 | 1.00 | 1.00 | 23 |

**Overall:** Accuracy = 0.99 | Macro Avg F1 = 0.99 | Weighted Avg F1 = 0.99

---

## 🚀 Installation

### Prerequisites

- Python 3.9+
- pip

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/GreenIntel-Smart-Farming.git
cd GreenIntel-Smart-Farming
```

### 2. Create Virtual Environment (Recommended)

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

### 5. Open in Browser

Navigate to: `http://127.0.0.1:5000`

---

## 📖 Usage

1. **Home Page** — Learn about the system and navigate to prediction.
2. **Predict Page** — Enter your soil and environmental values:
   - Nitrogen (N) content
   - Phosphorus (P) content
   - Potassium (K) content
   - Temperature (°C)
   - Humidity (%)
   - pH level
   - Rainfall (mm)
3. **Get Prediction** — The Random Forest model instantly recommends the most suitable crop.
4. **Analysis Dashboard** — View model performance, comparisons, and agricultural insights.

---

## 📂 Project Structure

```
GreenIntel-Smart-Farming/
│
├── static/                 # CSS, JS, Images
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/              # HTML Templates
│   ├── index.html          # Home Page
│   ├── predict.html        # Prediction Form
│   ├── analysis.html       # Data Analysis
│   ├── supervised.html     # Model Comparison
│   └── dashboard.html      # Performance Dashboard
│
├── dataset/
│   └── crop_dataset.csv    # Training Data
│
├── model/
│   └── crop_model.pkl      # Trained Random Forest Model
│
├── app.py                  # Flask Application
├── train_model.py          # Model Training Script
├── requirements.txt        # Python Dependencies
└── README.md               # Project Documentation
```

---

## 🌾 Supported Crops

The system can predict **22 different crops**:

| | | | |
|---|---|---|---|
| 🍚 Rice | 🌽 Maize | 🍌 Banana | 🥭 Mango |
| 🧶 Cotton | ☕ Coffee | 🥥 Coconut | 🍎 Apple |
| 🍊 Orange | 🍈 Papaya | 🍉 Watermelon | 🍇 Grapes |
| 🫘 Chickpea | 🫘 Lentil | 🫘 Kidney Beans | 🫘 Pigeonpeas |
| 🫘 Blackgram | 🫘 Mungbean | 🫘 Mothbeans | 🌿 Jute |
| 🍈 Muskmelon | 🍎 Pomegranate | | |

---

## 📸 System Screenshots

### 🏠 Home Page
*🌾 Crop Prediction*

### 📊 Analysis Dashboard
*📈 MSP Graphs*

---

## 🛣️ Roadmap

- [x] Core crop prediction with Random Forest
- [x] Web interface with Flask
- [x] Model comparison dashboard
- [ ] 🌦️ Weather API Integration
- [ ] 🌱 Fertilizer Recommendation System
- [ ] 📱 Mobile Application (React Native / Flutter)
- [ ] ☁️ Cloud Deployment (AWS / Render / Heroku)
- [ ] 🌍 Multi-language Support
- [ ] 📷 Plant Disease Detection (CNN / Deep Learning)
- [ ] 📡 IoT Sensor Integration

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve GreenIntel:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code follows the existing style and includes appropriate tests.

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute for educational and research purposes.

See [LICENSE](LICENSE) for more details.

---

## 👨‍💻 Author

**Om Uniyal**
MCA (AI & Data Science) Student
Machine Learning & Web Development Enthusiast

[📧 omuniyal0@gmail.com](mailto:omuniyal0@gmail.com) • [🔗 GitHub](https://github.com/YOUR_USERNAME)

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub!
Your support helps keep the project alive and motivates future enhancements.

<div align="center">

Made with ❤️ for smarter farming

</div>
