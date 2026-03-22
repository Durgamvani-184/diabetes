# 🩺 Diabetes Prediction App

A Machine Learning-powered web application that predicts whether a person is likely to have diabetes based on medical parameters. This project helps in early diagnosis and promotes healthcare awareness using data-driven insights.

---

## 🚀 Features

- 🔍 Predicts diabetes risk instantly  
- 🧠 Uses trained Machine Learning model  
- 📊 Clean and simple user interface  
- ⚡ Fast and accurate predictions  
- 📁 Well-structured project architecture  

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS  
- **Backend:** Python (Flask)  
- **Machine Learning:** Scikit-learn, Pandas, NumPy  
- **Model:** Classification model (saved using Pickle)  

---

## 📁 Project Structure

```
Diabetes-App/
│── app/
│   └── app.py
│
│── model/
│   ├── model.pkl
│   └── scaler.pkl
│
│── data/
│   └── diabetes.csv
│
│── notebooks/
│   └── training.py
│
│── screenshots/
│   ├── home.png
│   ├── result.png
│   └── summary.png
│
│── README.md
│── requirements.txt
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Durgamvani-184/diabetes.git
cd diabetes
```

### 2. Create Virtual Environment (Optional)
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
python app/app.py
```

### 5. Open in Browser
```
http://127.0.0.1:5000/
```

---

## 📥 Input Parameters

- Pregnancies  
- Glucose Level  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

---

## 📤 Output

- ✅ Diabetic or ❌ Non-Diabetic  
- 📊 Prediction result based on ML model  

---

## 🧪 Model Training

- Data preprocessing and cleaning  
- Feature scaling using StandardScaler  
- Model training using classification algorithm  
- Model & scaler saved using pickle  

---

## 📸 Screenshots

### 🏠 Home Page
![Home](screenshots/home.png)

### 📊 Result Page
![Result](screenshots/result.png)

### 📈 Summary
![Summary](screenshots/summary.png)

---

## 🎯 Future Enhancements

- 📱 Responsive UI  
- ☁️ Cloud deployment (Render / AWS)  
- 📊 Visualization dashboard  
- 🤖 Improve accuracy with advanced models  

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Durgam Vani**  
🔗 https://github.com/Durgamvani-184
