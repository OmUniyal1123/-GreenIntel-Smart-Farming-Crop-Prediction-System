🌱 GreenIntel — Smart Farming & Crop Prediction System
<div align="center">
 Python 

 Flask 

 scikit-learn 

 License 

 Accuracy 
AI-powered crop recommendation system that helps farmers make data-driven decisions using Machine Learning.
🚀 Live Demo • 📊 Screenshots • 📖 Report Bug • ✨ Request Feature
</div>
📌 Table of Contents
Overview
Features
Tech Stack
ML Model Performance
Installation
Usage
Project Structure
Supported Crops
Screenshots
Roadmap
Contributing
License
Contact
🎯 Overview
Agriculture is the backbone of the economy, yet farmers frequently struggle with crop selection based on soil and climate conditions. Choosing the wrong crop leads to reduced yield, wasted resources, and financial loss.
GreenIntel solves this problem using a Random Forest Machine Learning model trained on agricultural data. By analyzing 7 key parameters — Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall — the system predicts the most suitable crop with 99.24% accuracy.
💡 Empowering farmers with AI-driven insights for smarter, more productive farming.
✨ Features
Table
Feature	Description
🤖 AI Crop Prediction	Predicts the best crop based on soil & environmental data
📊 Data Analysis	Visualizes soil and environmental parameter distributions
🏆 Model Comparison	Benchmarks 5 ML algorithms to find the best performer
🌐 Web Interface	Clean, responsive Flask app with real-time predictions
📈 Dashboard	Interactive charts for performance visualization
⚡ Real-Time	Instant predictions with no latency
🛠️ Tech Stack
Frontend
 HTML5 

 CSS3 

 JavaScript 

 Bootstrap 
Backend & ML
 Python 

 Flask 

 scikit-learn 

 Pandas 

 NumPy 

 Matplotlib 

 Seaborn 
🧠 ML Model Performance
The project evaluates 5 supervised learning algorithms on the crop recommendation dataset (660 samples, 22 crop classes):
Table
Rank	Algorithm	Accuracy
🥉	Logistic Regression	95.15%
🥈	SVM	96.36%
🥉	KNN	97.72%
🥈	Decision Tree	98.63%
🥇	Random Forest	99.24% ✅
Cross-Validation Accuracy: 99.40%
Classification Report (Random Forest)
Table
Crop	Precision	Recall	F1-Score	Support
Apple	1.00	1.00	1.00	34
Banana	1.00	1.00	1.00	26
Blackgram	1.00	1.00	1.00	26
Chickpea	1.00	1.00	1.00	34
Coconut	1.00	1.00	1.00	33
Coffee	1.00	1.00	1.00	30
Cotton	1.00	1.00	1.00	28
Grapes	1.00	1.00	1.00	23
Jute	0.87	1.00	0.93	34
Kidneybeans	1.00	1.00	1.00	36
Lentil	1.00	1.00	1.00	22
Maize	1.00	1.00	1.00	26
Mango	1.00	1.00	1.00	32
Mothbeans	1.00	1.00	1.00	34
Mungbean	1.00	1.00	1.00	30
Muskmelon	1.00	1.00	1.00	24
Orange	1.00	1.00	1.00	25
Papaya	1.00	1.00	1.00	37
Pigeonpeas	1.00	1.00	1.00	37
Pomegranate	1.00	1.00	1.00	38
Rice	1.00	0.82	0.90	28
Watermelon	1.00	1.00	1.00	23
Overall: Accuracy = 0.99 | Macro Avg F1 = 0.99 | Weighted Avg F1 = 0.99
🚀 Installation
Prerequisites
Python 3.9+
pip
1. Clone the Repository
bash
git clone https://github.com/YOUR_USERNAME/GreenIntel-Smart-Farming.git
cd GreenIntel-Smart-Farming
2. Create Virtual Environment (Recommended)
bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
3. Install Dependencies
bash
pip install -r requirements.txt
4. Run the Application
bash
python app.py
5. Open in Browser
Navigate to: http://127.0.0.1:5000
📖 Usage
Home Page — Learn about the system and navigate to prediction.
Predict Page — Enter your soil and environmental values:
Nitrogen (N) content
Phosphorus (P) content
Potassium (K) content
Temperature (°C)
Humidity (%)
pH level
Rainfall (mm)
Get Prediction — The Random Forest model instantly recommends the most suitable crop.
Analysis Dashboard — View model performance, comparisons, and agricultural insights.
📂 Project Structure
plain
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
🌾 Supported Crops
The system can predict 22 different crops:
Table
🍚 Rice	🌽 Maize	🍌 Banana	🥭 Mango
🧶 Cotton	☕ Coffee	🥥 Coconut	🍎 Apple
🍊 Orange	🍈 Papaya	🍉 Watermelon	🍇 Grapes
🫘 Chickpea	🫘 Lentil	🫘 Kidney Beans	🫘 Pigeonpeas
🫘 Blackgram	🫘 Mungbean	🫘 Mothbeans	🌿 Jute
🍈 Muskmelon	🍎 Pomegranate		
📸 System Screenshots
🏠 Home Page
🌾 Crop Prediction

📊 Analysis Dashboard
📈 MSP Graphs

🛣️ Roadmap
[x] Core crop prediction with Random Forest
[x] Web interface with Flask
[x] Model comparison dashboard
[ ] 🌦️ Weather API Integration
[ ] 🌱 Fertilizer Recommendation System
[ ] 📱 Mobile Application (React Native / Flutter)
[ ] ☁️ Cloud Deployment (AWS / Render / Heroku)
[ ] 🌍 Multi-language Support
[ ] 📷 Plant Disease Detection (CNN / Deep Learning)
[ ] 📡 IoT Sensor Integration
🤝 Contributing
Contributions are welcome! If you'd like to improve GreenIntel:
Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
Please ensure your code follows the existing style and includes appropriate tests.
📄 License
This project is licensed under the MIT License — feel free to use, modify, and distribute for educational and research purposes.
See LICENSE for more details.
👨‍💻 Author
Om Uniyal
MCA (AI & Data Science) Student
Machine Learning & Web Development Enthusiast
mailto:omuniyal0@gmail.com
https://github.com/YOUR_USERNAME
⭐ Support
If you found this project useful, please consider giving it a ⭐ on GitHub!
Your support helps keep the project alive and motivates future enhancements.
<div align="center">
Made with ❤️ for smarter farming
</div>
