# 🩺 Breast Cancer Detection Web App




## 📌 Overview
This Breast Cancer Detection Web App is a machine learning-powered Flask application that predicts whether a tumor is benign or malignant. The model is trained on the Wisconsin Breast Cancer dataset using Scikit-learn, and predictions are displayed through an interactive web interface.

## 🚀 Features
✅ 95% accuracy in cancer prediction using ML algorithms.
✅ Flask-based API for real-time predictions.
✅ Interactive UI built with HTML, CSS, and Bootstrap.
✅ Fast processing time with response latency under 200ms.
✅ Pre-trained model integration using pickle for efficient loading.

## 🏗️ Tech Stack
Frontend: HTML, CSS, Bootstrap
Backend: Flask (Python)
Machine Learning: Scikit-learn, Pandas, NumPy
Model Storage: Pickle
Version Control: Git & GitHub
🔧 Installation & Setup
1️⃣ Clone the Repository

sh
Copy
Edit
git clone https://github.com/pandeySAN/Breast-Cancer-prediction
cd breast-cancer-detection
2️⃣ Create a Virtual Environment (Optional but Recommended)

sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate      # Windows
3️⃣ Install Dependencies

sh
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the Flask App

sh
Copy
Edit
python app.py
🔹 Open http://127.0.0.1:5000/ in your browser to access the app.

## 📝 Usage
1️⃣ Upload patient tumor feature values via the UI.
2️⃣ Click Predict to get an instant result.
3️⃣ View model prediction as Benign or Malignant.

## 📊 Model Performance
Dataset: Wisconsin Breast Cancer dataset
Algorithm: Logistic Regression
Accuracy: 95%
False Positive Reduction: 10%
🛠️ Folder Structure
php
Copy
Edit
📂 breast-cancer-detection
 ├── 📁 template         # HTML templates for Flask UI
 │   ├── index.html      # Main UI page
 ├── 📁 static           # CSS, images, etc.
 ├── app.py             # Flask app main file
 ├── model.pkl          # Pre-trained ML model
 ├── data.csv           # Dataset used for training
 ├── requirements.txt   # Dependencies
 ├── README.md          # Project documentation
📌 Future Improvements
🚀 Add deep learning models for higher accuracy.
🚀 Implement Docker for easy deployment.
🚀 Deploy on AWS/GCP/Heroku for global access.

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repo and submit a pull request.

## 📬 Contact
📧 Email: sancpan02@gmail.com
🔗 LinkedIn: www.linkedin.com/in/sanchit-pandey-4682b724a
🔗 GitHub: pandeySAN

