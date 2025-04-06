# 🚴‍♂️ Bike Matching API

This is a simple FastAPI-based backend service that matches users with available bikes nearby based on their **location** and **riding preferences**.

---

## 🔍 What It Does

- Accepts user location and preferences via an API request
- Finds available bikes near that location
- Returns the best matches (based on availability, type, etc.)

---

## ⚙️ Tech Stack

- **FastAPI** – Lightweight Python web framework
- **Uvicorn** – ASGI server for running the app
- **Pytest** – For testing the API endpoints

---

## 📦 Installation

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
2.Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3.Install dependencies:
pip install -r requirements.txt
4.Run the API:
uvicorn app.main:app --reload
