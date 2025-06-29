# 🚘 AI-Based Vehicle Recommendation System

An intelligent, AI-powered web application that recommends suitable vehicles (Scooter, Bike, or Car) to users based on **age** and **monthly salary**. It combines **machine learning** with a clean **Streamlit frontend** to help users make informed decisions, complete with predicted prices, mileage, fuel type, EMI options, and even **local showroom suggestions**.

---

## 📌 Key Features

- ✅ Personalized vehicle recommendations (Scooters, Bikes, Cars).
- ✅ Real-time price prediction using Linear Regression.
- ✅ Car recommendations based on rule-based salary filters.
- ✅ EMI options calculated dynamically.
- ✅ Integrated showroom locator (Google Maps embedded).
- ✅ Fully responsive and styled **Streamlit UI** with background image and animations.
- ✅ User-friendly multi-page interface with persistent state.

---

## 🧰 Tech Stack

| Layer                | Tools & Libraries                             |
| -------------------- | --------------------------------------------- |
| **Frontend**   | Streamlit (custom CSS styling, session state) |
| **Backend**    | Flask (REST API for recommendations)          |
| **ML**         | Scikit-learn, LinearRegression, LabelEncoder  |
| **Data**       | Pandas, CSV files                             |
| **Deployment** | Localhost (or deploy via Streamlit/Heroku)    |

---

## 📁 Folder Structure

vehicle-recommender/
├── backend/
│ └── app.py # Flask API for recommendations
├── frontend/
│ └── streamlit_app.py # Streamlit frontend UI
├── data/
│ ├── updated_expanded_vehicle.csv
│ ├── updated_expanded_car.csv
│ └── showrooms1.csv
├── requirements.txt # Python dependencies
└── README.md----render.yaml


## ⚙️ How to Run the Project

### 🔹 Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/vehicle-recommender.git
cd vehicle-recommender
```

### 🔹 Step 2: Install Dependencies

Make sure you have **Python 3.7+** and **pip** installed.

```
pip install -r requirements.txt
```

### 🔹 Step 3: Run Flask Backend

```
cd backend
python app.py
```

This will start the API on `http://localhost:5000`

You’ll see model accuracy printed in the terminal.

### 🔹 Step 4: Run Streamlit Frontend

Open a new terminal:

```
cd frontend
streamlit run streamlit_app.py
```

The app will launch in your browser on `http://localhost:8501`

✍️ Authors SNEHITH AMBEWAR.
