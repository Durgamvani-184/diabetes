🩺 Diabetes Prediction App

A Machine Learning-powered web application that predicts whether a person is likely to have diabetes based on medical parameters. This project aims to assist in early diagnosis and healthcare awareness using data-driven insights.

🚀 Features
🔍 Predicts diabetes risk instantly
🧠 Uses trained Machine Learning model
📊 Clean and simple user interface
⚡ Fast and accurate predictions
📁 Well-structured project architecture
🛠️ Tech Stack
Frontend: HTML, CSS
Backend: Python (Flask)
Machine Learning: Scikit-learn, Pandas, NumPy
Model: Trained classification model (saved using Pickle)
📁 Project Structure
Diabetes-App/
│── app/
│   └── app.py                # Web application
│
│── model/
│   ├── model.pkl            # Trained ML model
│   └── scaler.pkl           # Saved scaler
│
│── data/
│   └── diabetes.csv         # Dataset
│
│── notebooks/
│   └── training.py          # Model training script
│
│── screenshots/             # Application images
│   ├── home.png
│   ├── result.png
│   └── summary.png
│
│── README.md
│── requirements.txt
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Durgamvani-184/diabetes.git
cd diabetes
2️⃣ Create Virtual Environment (optional)
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python app/app.py
5️⃣ Open in Browser
http://127.0.0.1:5000/
📥 Input Parameters

The application uses the following medical features:

Pregnancies
Glucose Level
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
📤 Output
✅ Diabetic or ❌ Non-Diabetic
📊 Prediction result based on ML model
🧪 Model Training
Data preprocessing and cleaning
Feature scaling using StandardScaler
Model training using classification algorithm
Model & scaler saved using pickle
📸 Screenshots
🏠 Home Page

📊 Prediction Result

📈 Summary

🎯 Future Enhancements
📱 Responsive UI (mobile-friendly)
☁️ Cloud deployment (Render / AWS)
📊 Visualization dashboard
🤖 Improve accuracy with advanced ML/DL models
🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

📄 License

This project is licensed under the MIT License.

👩‍💻 Author

Durgam Vani
🔗 GitHub: https://github.com/Durgamvani-184
