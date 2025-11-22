# 🛒 Seller Hub

# 🚀 Seller Hub System

An AI-powered Seller Platform inspired by Amazon Polaris and Walmart Seller Hub — built with React, Python (Flask/FastAPI), SQLite, Random Forest ML, Gemini API, and Leaflet Maps.

Backend Repository: https://github.com/Samtoosoon/backend_polaris  
ML App Demo: https://polarisoptimizer.streamlit.app/

 
📊 **[Pitch Deck / PPT (Canva)](https://www.canva.com/design/DAG5M4tsCTQ/e_fr774Qs5SgLH32ucJWUA/edit)**  

🌐 **[Live Demo (Deployed Link)](https://seller-hub-bm8t.vercel.app/)**  


## ✨ Features

### 📊 Dashboard & Analytics (Prototype)

- Interactive dashboard with simulated key metrics: **revenue, orders, and trends**
- Built using **hardcoded sample data** to demonstrate **UI/UX flow** and potential business insights


### 🗺️ Order Fulfillment

- **Delivery Map**: Leaflet-based simulated delivery locations
- **Warehouse Logic**: Detects nearest warehouse (e.g., Noida) using basic geo-calculations
- **Route Optimization**:
  - Shows estimated distance, delivery time, and charges  
  - _Example: ₹163 for 31.57 km_


### 🤖 AI Assistant (Gemini API)

Integrated Gemini-powered assistant to help sellers:

- Optimize **product titles** and **descriptions**
- Generate **keywords** and **SEO strategies**
- Analyze **competitors** and **sales strategy**
- **Voice input** support and **multilingual** output


### 🔍 Product Visibility Predictor (Python ML)

- Uses a **Random Forest** model to predict listing visibility
- Input: title, price stability, stock status, pincodes, etc.
- Output: **visibility score** based on Polaris-like logic


## 🛠️ Tech Stack

### Frontend
- React.js, JavaScript (ES6+), CSS3
- Chart.js / Recharts (visualizations)
- Leaflet / OpenStreetMap (maps)

### Backend & AI
- Gemini API (AI assistant)
- Python (Flask/FastAPI) for ML endpoint
- Trained Random Forest model for visibility predictions


