# CGPA → Package Predictor 📈

A light-weight web app that estimates a student’s expected campus placement package (in LPA) based on their CGPA. Built with Python, scikit-learn and Streamlit.  

---

## 🔎 Overview

- Takes **CGPA** as input (on a 4.0–10.0 scale).  
- Applies a trained linear regression model to predict **package (in LPA)**.  
- Displays a friendly message like:  
  > “Hello *Name*, this is just a simple prediction — you can absolutely earn more than this. Stay hungry, stay sharp.”  

Goal: Provide a **quick motivational estimate** — not a guarantee. Use it to gauge scope, not replace hard work.

---

## 🛠 Tech Stack

- Python 3.x  
- scikit-learn  
- Streamlit  
- pandas / numpy  

---

## 🚀 How to Run / Deploy

1. Clone or download the repo.  
2. Ensure the folder contains:
   - `app.py` — main Streamlit app  
   - `cgpa_package_model.pkl` — trained model file  
   - `requirements.txt` — for dependencies  
3. (Optional local test)  
   ```bash
   pip install -r requirements.txt
   streamlit run app.py
