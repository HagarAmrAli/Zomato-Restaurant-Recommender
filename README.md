# Zomato-Restaurant-Recommender

# 🍽️ Zomato Restaurant Recommender System

A **knowledge-based restaurant recommender system** built using the Zomato dataset. This app allows users to filter restaurants based on preferences like cuisine, city, price range, and online delivery availability, with dynamic ranking and downloadable results.

🚀 **Live App**: [Try it on Streamlit](https://zomato-restaurant-recommender-8cxejuu4lumvznmgeafhck.streamlit.app/)

---

## 📌 Features
- 🔍 Filter restaurants by **cuisine**, **city**, **price range**, and **online delivery**.
- 📊 Rank results by **score**, **rating**, or **cost**.
- 🗺️ Open restaurant locations in **Google Maps**.
- 🧠 Provide knowledge-based explanations for recommendations.
- 📁 Download recommendations as a CSV file.
- 🎈 Interactive Streamlit web interface with user-friendly controls.

---

## 📂 Project Structure
zomato_recommender_project/
│
├── data/
│   └── zomato.csv          # Dataset file
│
├── main.py                 # Streamlit app entry point
├── data_preprocessing.py   # Data loading and cleaning logic
├── recommender.py          # Filtering and ranking logic
├── utils.py                # Functions for explanations and map links
├── requirements.txt        # Python dependencies
└── README.md               # This file

