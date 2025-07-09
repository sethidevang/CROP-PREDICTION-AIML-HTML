
# 🌾 Crop Predictor – Agrology Web App

**Crop Predictor** is a Flask-powered web application that uses machine learning to suggest the most suitable crop for a given set of soil and environmental conditions. It brings together the power of data and simplicity of design to make agriculture smarter, all under the vision of **Agrology**—the intersection of agriculture and technology.

🔗 **Live Demo**: [https://sethidevang.pythonanywhere.com/](https://sethidevang.pythonanywhere.com/)

---

## 🧠 What It Does

Farmers and users enter the following inputs:
- 🌡️ Temperature
- 💧 Humidity
- 🌧️ Rainfall
- 🧪 pH level
- 🌱 Nitrogen (N)
- 🧬 Phosphorus (P)
- 🧪 Potassium (K)
- 🏜️ Soil Type (e.g., Sandy)

The system then uses a machine learning model to **predict the most appropriate crop** for the given environment.

---

## 🛠️ Tech Stack

### Backend
- **Python**
- **Flask**
- **Scikit-learn** for ML model training and prediction

### Frontend
- **HTML5**
- **CSS3** for clean UI
- **Jinja2** templates

### Hosting
- **PythonAnywhere** (Free hosting for Python web apps)

---

## 🧪 How It Works

1. **Data Input:** Users input environmental and soil parameters.
2. **Prediction Engine:** A trained machine learning model runs in the Flask backend.
3. **Output:** The predicted crop is rendered on the result page.

---

## 📸 Preview

> *(Screenshots of the homepage, form input, and result page can go here)*

---

## 🚀 How to Run Locally

### 📦 Requirements

```bash
pip install flask scikit-learn pandas
```

### 🧪 Run App

```bash
python app.py
```

Then open [http://localhost:5000](http://localhost:5000) in your browser.

---

## 🌱 Example Use Case

```text
Temperature: 26°C
Humidity: 80%
Rainfall: 200 mm
Nitrogen: 90
Phosphorus: 42
Potassium: 43
pH: 6.5
Soil Type: Sandy

→ Predicted Crop: Rice 🌾
```

---

## 📌 Future Improvements

- Add more granular soil types and micronutrient data
- API version for mobile & external integration
- Add user authentication to save predictions
- Graph visualizations for crop trends

---

## 👨‍💻 Developed By

**Devang Sethi**  
- Passionate about bridging tech with real-world problems  
- [🌐 Portfolio](https://devangsethi.vercel.app/)

---

## 🧠 The Vision: Agrology

> _“Agrology is my vision to blend agriculture with intelligence—leveraging code, data, and automation to empower farmers globally.”_

Crop Predictor is a stepping stone in that journey.

---

## ✨ Final Note

This project was built entirely by me—from designing the ML model and building the Flask backend to designing the UI with HTML/CSS. It reflects my belief that even a small project can create real impact when built with purpose.

> 🌾 _“Let’s grow with data. Let’s grow with Crop Predictor.”_
