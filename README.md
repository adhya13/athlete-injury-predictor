# 🏥 Athlete Injury Recovery Prediction

This project uses Machine Learning and Flask to predict **how long it will take an athlete to recover from an injury**, based on input features like injury type, severity, treatment, etc.

---

## 🚀 Features

- Predicts recovery duration for athletes
- Built with Flask (Python web framework)
- Uses ML model trained on CSV data
- Visualizations using Matplotlib and Seaborn
- Deployable on Render (free hosting)

---

## 🧰 Tech Stack

- Python 3.10+
- Flask
- Scikit-learn
- Pandas
- Matplotlib, Seaborn
- SQLAlchemy
- PostgreSQL (or SQLite for local testing)

---

## 🛠️ Local Setup

### ✅ 1. Clone the repository

git clone https://github.com/yourusername/athlete-injury-predictor.git
cd athlete-injury-predictor
✅ 2. Create & activate virtual environment
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate   # On Windows

✅ 3. Install dependencies
pip install -r requirements.txt

✅ 4. Run the app

python application.py
App will run on: http://127.0.0.1:5000

🌐 Deployment (Render)
🔹 Requirements
requirements.txt

Procfile

application.py (main file)

Push to GitHub

🔹 Procfile Example
makefile
Copy
Edit
web: gunicorn application:app
🔹 Start Command on Render

gunicorn application:app
📂 Project Structure

├── application.py         # Main Flask file
├── requirements.txt
├── Procfile
├── injury1.csv            # Dataset
├── templates/             # HTML templates (Flask)
├── static/                # CSS/JS files
└── README.md


✍️ Credits
Developed as part of a Machine Learning project for academic/portfolio use.

