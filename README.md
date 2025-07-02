## 📊✨ Salary Prediction Website

[![Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-FF4B4B?logo=streamlit\&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/)
[![Last Commit](https://img.shields.io/github/last-commit/Alok-2002/Salary_Prediction_Website)](https://github.com/Alok-2002/Salary_Prediction_Website)
[![Deploy to Streamlit Cloud](https://img.shields.io/badge/Deploy%20to-Streamlit%20Cloud-orange?logo=streamlit)](#)

> 🔍 Explore developer salary trends, 📈 visualize insights, and 🤖 predict your potential earnings — all in a click!

---

## 📸 Screenshots

### 🏠 Home / Explore Page

![image](https://github.com/user-attachments/assets/ed59e0bc-0bdf-4e03-85c0-c0d767196d49)


### 🔮 Predict Page

![image](https://github.com/user-attachments/assets/254b969f-0a09-4aec-aae8-ff249c4291c3)


## 🌟 What’s Inside?

✨ **Interactive data exploration** – Dive into the developer survey (survey\_2021.csv)
⚙️ **Smart salary predictions** – Enter your details to predict your salary using our trained ML model
🖼️ **Beautiful UI** – Powered by Streamlit, clean and intuitive

---

## 🛠️ Tech Stack

* Python 🐍
* Streamlit ⚡
* Scikit-learn 🤖
* Pandas 🐼
* Pickle (for saving/loading ML model)

---

## 📂 Project Structure

```
.
├── app.py                # Streamlit entry point
├── explore_page.py       # Data visualization page
├── predict_page.py       # Salary prediction page
├── Salary2020.pkl        # Trained ML model
├── survey_2021.csv       # Developer survey dataset
└── requirements.txt      # Project dependencies
```

---

## 🚀 Quick Start

### 📦 Installation

Clone this repo and install dependencies:

```bash
git clone https://github.com/your-username/salary-prediction-website.git
cd salary-prediction-website
pip install -r requirements.txt
```

### ▶️ Run locally

```bash
streamlit run app.py
```

Then open: [http://localhost:8501](http://localhost:8501)

---

## ☁️ Deployment Guide (Streamlit Cloud)

1. Push your project to GitHub
2. Go to [Streamlit Cloud](https://streamlit.io/cloud)
3. Click **"New app"** and connect your GitHub repo
4. Set the **main file** as `app.py`
5. Click **Deploy** – done! 🎉

---

## 📊 Dataset

Includes real-world developer data:

* Country, education, years of coding, developer type
* Programming languages, databases, frameworks
* Annual compensation & more

---

## 🤖 Model

* Trained using scikit-learn
* Saved as `Salary2020.pkl`
* Predicts salary based on user input (education, experience, dev type, etc.)

---

## 🔧 `requirements.txt` template

```txt
streamlit==1.25.0
pandas==2.0.0
scikit-learn==1.2.2
numpy==1.24.2
```

## ✨ Live Demo

🚀 [Launch the App on Streamlit Cloud](https://salary-prediction-website.streamlit.app/)

---

## 👨‍💻 Author

Crafted with ❤️ by [Alok Sharma](https://github.com/Alok-2002)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
