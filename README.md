# 🌱 GreenIntel — Smart Farming & Crop Recommendation System

<p align="center">
  <img src="static/images/banner.png" alt="GreenIntel Banner" width="100%">
</p>

<p align="center">
  <b>AI-Powered Crop Recommendation System using Machine Learning</b><br>
  Helping farmers make data-driven decisions for higher productivity and sustainable agriculture.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_App-black?logo=flask)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Machine_Learning-orange?logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-green)
![Accuracy](https://img.shields.io/badge/Accuracy-99.24%25-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</p>

---

# 📖 Table of Contents

* Overview
* Problem Statement
* Features
* System Architecture
* Technology Stack
* Dataset
* Machine Learning Pipeline
* Model Performance
* Installation
* Usage
* API Routes
* Project Structure
* Supported Crops
* Exploratory Data Analysis
* Screenshots
* Future Roadmap
* Contributing
* License
* Author
* Acknowledgements

---

# 🎯 Overview

Agriculture plays a vital role in the economy, yet many farmers still rely on traditional methods when selecting crops. Choosing an unsuitable crop for a particular soil and climate condition often results in reduced productivity, unnecessary fertilizer usage, and financial losses.

**GreenIntel** is an AI-powered Crop Recommendation System that uses Machine Learning to recommend the most suitable crop based on soil nutrients and environmental conditions.

The system analyzes:

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* pH
* Rainfall

Using these parameters, GreenIntel predicts the best crop with **99.24% testing accuracy** using the **Random Forest Classifier**.

---

# ❗ Problem Statement

Farmers often face difficulties selecting the most suitable crop because of changing climate conditions and varying soil characteristics.

Traditional decision-making may lead to:

* Poor crop yield
* Excessive fertilizer usage
* Water wastage
* Financial loss
* Reduced agricultural productivity

GreenIntel aims to solve this problem using Artificial Intelligence and Machine Learning.

---

# ✨ Features

| Feature               | Description                               |
| --------------------- | ----------------------------------------- |
| 🌱 AI Crop Prediction | Predicts the most suitable crop using ML  |
| 📊 Data Analysis      | Visualizes soil and weather distributions |
| 📈 Dashboard          | Displays model comparison and insights    |
| ⚡ Instant Prediction  | Real-time prediction using Flask          |
| 🧠 Machine Learning   | Random Forest based prediction            |
| 📉 Model Comparison   | Compare 5 supervised algorithms           |
| 💻 Responsive UI      | User-friendly web interface               |
| 📂 Modular Code       | Easy to understand project structure      |

---

# 🏗️ System Architecture

```text
                    Farmer

                       │

                       ▼

             Enter Soil Parameters

                       │

                       ▼

              Flask Web Application

                       │

                       ▼

        Data Preprocessing & Validation

                       │

                       ▼

       Random Forest Prediction Model

                       │

                       ▼

         Recommended Crop Displayed
```

---

# 🛠 Technology Stack

## Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

## Backend

* Python
* Flask

## Machine Learning

* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Tools

* VS Code
* Jupyter Notebook
* Git
* GitHub

---

# 📊 Dataset

**Dataset Name**

Crop Recommendation Dataset

**Source**

Agricultural Dataset (Kaggle)

## Dataset Statistics

| Property        | Value     |
| --------------- | --------- |
| Samples         | 2200      |
| Features        | 7         |
| Crop Classes    | 22        |
| Target Variable | Crop Name |

### Input Features

* Nitrogen
* Phosphorus
* Potassium
* Temperature
* Humidity
* pH
* Rainfall

---

# 🤖 Machine Learning Pipeline

```text
Data Collection

↓

Data Cleaning

↓

Exploratory Data Analysis

↓

Train-Test Split

↓

Feature Engineering

↓

Model Training

↓

Hyperparameter Tuning

↓

Cross Validation

↓

Model Evaluation

↓

Save Model (.pkl)

↓

Flask Deployment
```

---

# 🧠 Algorithms Compared

| Algorithm              | Accuracy     |
| ---------------------- | ------------ |
| Logistic Regression    | 95.15%       |
| Support Vector Machine | 96.36%       |
| K-Nearest Neighbors    | 97.72%       |
| Decision Tree          | 98.63%       |
| **Random Forest**      | **99.24%** ✅ |

---

# 🏆 Why Random Forest?

Random Forest achieved the highest accuracy because:

* Handles nonlinear relationships efficiently.
* Reduces overfitting using ensemble learning.
* Performs well with mixed numerical features.
* Robust against noisy data.
* Requires minimal preprocessing.
* Produces stable predictions.

---

# 📈 Model Performance

## Testing Accuracy

**99.24%**

## Cross Validation Accuracy

**99.40%**

## Precision

99%

## Recall

99%

## F1 Score

99%

---

# 📋 Classification Report (Summary)

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 0.99  |
| Precision | 0.99  |
| Recall    | 0.99  |
| F1 Score  | 0.99  |

Most crop classes achieved perfect precision and recall.

---

# 📊 Confusion Matrix

Add your confusion matrix screenshot here.

```text
images/confusion_matrix.png
```

---

# 📈 Exploratory Data Analysis

The project includes multiple visualizations:

* Feature Distribution
* Correlation Heatmap
* Crop Distribution
* Pair Plot
* Box Plot
* Histogram
* Scatter Plot

Place screenshots inside:

```text
static/images/
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/GreenIntel-Smart-Farming.git
```

```bash
cd GreenIntel-Smart-Farming
```

---

## Create Virtual Environment

Windows

```bash
python -m venv venv

venv\Scripts\activate
```

Linux/macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
python app.py
```

---

## Open Browser

```
http://127.0.0.1:5000
```

---

# 📖 Usage

### Home Page

Introduction to GreenIntel.

### Predict Crop

Enter

* Nitrogen
* Phosphorus
* Potassium
* Temperature
* Humidity
* pH
* Rainfall

Click **Predict**.

The Random Forest model instantly recommends the most suitable crop.

---

# 🌐 API Routes

| Route       | Description      |
| ----------- | ---------------- |
| /           | Home Page        |
| /predict    | Crop Prediction  |
| /analysis   | Data Analysis    |
| /dashboard  | Dashboard        |
| /supervised | Model Comparison |

---

# 📂 Project Structure

```text
GreenIntel-Smart-Farming
│
├── dataset
│   └── crop_dataset.csv
│
├── model
│   └── crop_model.pkl
│
├── static
│   ├── css
│   ├── js
│   ├── images
│
├── templates
│   ├── index.html
│   ├── predict.html
│   ├── analysis.html
│   ├── dashboard.html
│   └── supervised.html
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 🌾 Supported Crops

* Rice
* Maize
* Chickpea
* Kidney Beans
* Pigeon Peas
* Moth Beans
* Mung Bean
* Black Gram
* Lentil
* Pomegranate
* Banana
* Mango
* Grapes
* Watermelon
* Muskmelon
* Apple
* Orange
* Papaya
* Coconut
* Cotton
* Jute
* Coffee

---

# 📸 Screenshots

## Home Page

```
static/images/home.png
```

---

## Prediction Page

```
static/images/predict.png
```

---

## Dashboard

```
static/images/dashboard.png
```

---

## Model Comparison

```
static/images/model_comparison.png
```

---

## Confusion Matrix

```
static/images/confusion_matrix.png
```

---

# 📌 Future Roadmap

* ✅ Crop Recommendation
* ✅ Flask Web Application
* ✅ Dashboard
* ✅ Model Comparison

Upcoming Features

* Weather API Integration
* Fertilizer Recommendation
* CNN-based Plant Disease Detection
* Multi-language Support
* Android Application
* Cloud Deployment (AWS/Render)
* IoT Sensor Integration
* Voice Assistant for Farmers
* Satellite Image Analysis
* Yield Prediction

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature/new-feature
```

3. Commit changes.

```bash
git commit -m "Added new feature"
```

4. Push changes.

```bash
git push origin feature/new-feature
```

5. Open a Pull Request.

---

# 📄 License

This project is licensed under the **MIT License**.

Feel free to use this project for educational and research purposes.

---

# 👨‍💻 Author

**Om Uniyal**

🎓 MCA (AI & Data Science)

🏫 Graphic Era Hill University, Dehradun

💻 Machine Learning | Python | Flask | Data Science

📧 Email: [omuniyal0@gmail.com](mailto:omuniyal0@gmail.com)

🐙 GitHub: https://github.com/YOUR_USERNAME

💼 LinkedIn: https://linkedin.com/in/YOUR_USERNAME

---

# 🙏 Acknowledgements

* Kaggle Crop Recommendation Dataset
* Scikit-learn Documentation
* Flask Documentation
* Python Community
* Open Source Contributors

---

# ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

Your support motivates future development and improvements.

---

<p align="center">

**🌱 Made with ❤️ for Smarter Farming and Sustainable Agriculture 🌾**

</p>
