# 📊✨ Salary Prediction Website

[![Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Repo Size](https://img.shields.io/github/repo-size/Alok-2002/Salary_Prediction_Website_Source_Code)
![Last Commit](https://img.shields.io/github/last-commit/Alok-2002/Salary_Prediction_Website_Source_Code)
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)
[![Deploy to Streamlit Cloud](https://img.shields.io/badge/Deploy%20to-Streamlit%20Cloud-orange?logo=streamlit)](https://salary-prediction-website.streamlit.app/)

> 🔍 Explore developer salary trends, 📈 visualize insights, and 🤖 predict your potential earnings — all with an intuitive Streamlit interface!

---

## 🌟 What’s Inside?

✨ **Interactive data exploration** – Dive into the developer survey dataset  
⚙️ **Smart salary predictions** – Predict your salary based on your profile  
🖼️ **Beautiful UI** – Built entirely in Python using Streamlit (no HTML/CSS/JS)  
🚀 **One-click deployment** – Live on Streamlit Cloud

---

## 👥 Team Members

| Name              | Role                                             | GitHub | LinkedIn |
| ----------------- | -----------------------------------------------  | ------ | -------- |
| **Alok Sharma**   | Project Head, ML Expert, Backend Engineer & Deployment Specialist | [Alok Sharma](https://github.com/Alok-2002) | [LinkedIn](https://www.linkedin.com/in/alok-sharma2002-/) |
| **Sanskriti Yadav** | Project Co-Head, Frontend Engineer             | [Sanskriti Yadav](https://github.com/sanskriti-yadav) | [LinkedIn](https://www.linkedin.com/in/alok-sharma2002-/) |

📧 Contact: [sharmaalok02gwl@gmail.com](mailto:sharmaalok02gwl@gmail.com)

---

## 📸 Screenshots

### 🏠 Explore Page
![Explore Page](https://github.com/Alok-2002/Salary_Prediction_Website_Source_Code/assets/93814546/41d4e634-5961-49ae-89d1-8ed8949f9736)

### 🔮 Predict Page
![Predict Page](https://github.com/Alok-2002/Salary_Prediction_Website_Source_Code/assets/93814546/3a122a59-d7e4-4957-b757-4eb807c727de)

---

## 📂 Project Structure

```plaintext
Salary_Prediction_Website_Source_Code/
├── Dataset/                       # Dataset for training & visualization
├── Website/                       # Streamlit web app code
│   ├── app.py                     # Entry point for Streamlit
│   ├── explore_page.py            # Data visualization page
│   └── predict_page.py            # Prediction page
├── Model Training/                # Model training notebook
│   └── Salary_Prediction_Website_ML_Model_Training.ipynb
├── Trained Model/                 # Pre-trained ML model
│   └── Salary2020.pkl
└── requirements.txt               # Project dependencies
````

---

## 🛠️ Tech Stack

* Python 🐍
* Streamlit ⚡
* Scikit-learn 🤖
* Pandas 🐼
* NumPy ➕
* Pickle (for saving/loading ML model)

---

## 🚀 Quick Start

### 📦 Installation

Clone this repo and install required dependencies:

```bash
git clone https://github.com/alok-2002/Salary_Prediction_Website_Source_Code.git
cd Salary_Prediction_Website_Source_Code
pip install -r requirements.txt
```

---

### ▶️ Run the Website Locally

Navigate to the website folder and run:

```bash
cd Website/
streamlit run app.py
```

Then open: [http://localhost:8501](http://localhost:8501)

---

## ✏️ Model Training

To retrain the salary prediction model:

```bash
cd Model Training/
# Open and run the Jupyter notebook:
Salary_Prediction_Website_ML_Model_Training.ipynb
```

---

## ☁️ Deployment Guide (Streamlit Cloud)

1. Push your project to GitHub
2. Go to [Streamlit Cloud](https://streamlit.io/cloud)
3. Click **"New app"** and connect your repo
4. Set `Website/app.py` as the entry point
5. Click **Deploy** – done! 🎉

---

## 📊 Dataset

Includes real-world developer data:

* Country, education, years of coding
* Developer type, languages, frameworks
* Annual compensation & more

---

## 🤖 Model

* Trained using scikit-learn
* Saved as `Salary2020.pkl`
* Predicts salaries based on user input like education, experience, developer type, etc.

---

## ✅ `requirements.txt` Example

```txt
streamlit==1.25.0
pandas==2.0.0
scikit-learn==1.2.2
numpy==1.24.2
```

---

## ✨ Live Demo

🚀 [Launch on Streamlit Cloud](https://salary-prediction-website.streamlit.app/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ⭐ Show your support

If you find this useful, please consider starring ⭐ the repository to help others discover it!

Crafted with ❤️ by [Alok Sharma](https://github.com/Alok-2002) & [Sanskriti Yadav](https://github.com/sanskriti-yadav)
