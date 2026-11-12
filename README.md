# premium_prediction_model
This project was built with the aim to learn FastAPI and to learn to integrate ML model, fastapi and streamlit, I followed CampusX's FastAPI series to build this project.

---

## Project Structure

Make sure your project directory contains the following files:
```text
fast-api/
│
├── app.py              # FastAPI backend
├── frontend.py         # Streamlit frontend UI
├── model.pkl           # Trained scikit-learn model pipeline
└── requirements.txt    # Project dependencies

## 🚀 Setup & Installation Guide

### Create a Virtual Environment
python -m venv myenv

### Activate the Virtual Environment
myenv\Scripts\activate

### Install Dependencies
pip install -r requirements.txt

## ▶️ Running the Application

### Run the FastAPI Backend
uvicorn app:app --reload

### Run the Streamlit Frontend
streamlit run frontend.py

The user interface will automatically launch in your browser (usually at http://localhost:8501)