# 🏥 Hospital Patient Records System

A simple web application to manage hospital patient records using **Flask** and **SQLite**.

## 📌 Features
- Add, Edit, Delete Patients
- Simple UI with HTML + CSS
- Flash messages for actions
- SQLite database

## ▶️ Run Locally
```bash
git clone https://github.com/yourusername/hospital-patient-records.git
cd hospital-patient-records
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows
pip install -r requirements.txt
python
>>> from app import db
>>> db.create_all()
>>> exit()
python app.py
