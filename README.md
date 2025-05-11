# 🚖 Uber Pickups in NYC – Streamlit App

This is a simple interactive web app built using **Streamlit** that analyzes Uber pickup data in New York City.

## 🔍 Features

- View and filter raw Uber pickup data  
- Visualize number of pickups by hour using bar charts  
- Explore pickup locations on a map based on selected hour  

## 📂 Dataset

The data is from [Streamlit's demo dataset](https://s3-us-west-2.amazonaws.com/streamlit-demo-data/uber-raw-data-sep14.csv.gz), containing Uber pickup records for NYC in September 2014.

## ▶️ How to Run

```bash
pip install streamlit pandas numpy
streamlit run app.py
