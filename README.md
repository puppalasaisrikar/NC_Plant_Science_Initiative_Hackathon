## 🏆 Hackathon Winner - NC Plant Science Initiative, NC State
![Hackathon Winner](https://img.shields.io/badge/Hackathon-Winner-brightgreen)
Achieved **first place** in the prestigious hackathon organized by the NC Plant Science Initiative. Designed and implemented an ensemble of advanced machine learning models, including **Random Forest, K-Nearest Neighbors (KNN), Linear Regression, Lasso, and Ridge Regression**, to accurately predict critical plant and soil parameters, driving precision agriculture solutions.

---

## 🚀 Project Goal
The goal of this project was to **predict yield proxies for basil plants** (biomass and plant height) using soil parameter measurements. By leveraging machine learning techniques, we developed a robust predictive model to assist growers in optimizing conditions for basil cultivation.

## 📅 Timeline
- **Start Date:** October 18, 2024  
- **End Date:** October 20, 2024

---

## 🌱 Problem Description
The project involved multiple stages:
1. **Data Collection:** Measurements of key soil parameters like:
   - **pH**
   - **Electrical Conductivity (EC)**
   - **Moisture Content**

2. **Model Development:** Using collected data to train ML models that establish correlations between soil conditions and basil plant yield proxies:
   - **Biomass (fresh weight)**
   - **Plant Height**

3. **Deployment:** Model integrated into an interactive dashboard where users can input their soil measurements and receive real-time yield predictions.

---

## 📊 Dataset Description

### **Basil Plant Dataset**
- **Training Data:** 64 collected samples
- **Testing Data:** 11 mystery pots for model evaluation

### **Files Included:**
- `train_data.csv`: Training dataset with soil parameters and yield proxies
- `sample_soil_submission.csv`: Template for soil measurement submissions
- `sample_ml_submission.csv`: Template for model prediction submissions

### **Data Columns:**
- `sample_id`: Unique ID for each basil pot
- `avg_pH`: Average pH level of the soil
- `avg_EC`: Average electrical conductivity (μS)
- `avg_moisture`: Average soil moisture content (%)
- `biomass`: Fresh weight of biomass (grams)
- `plant_height`: Plant height (millimeters)

---

## 🧠 Machine Learning Approach
We utilized an **ensemble of machine learning models** to improve prediction accuracy:

- **Data Preprocessing:**
  - Normalization using **MinMaxScaler**
  - Handling missing values

- **Models Implemented:**
  - **Linear Regression**
  - **Ridge Regression**
  - **Lasso Regression**
  - **K-Nearest Neighbors (KNN)**
  - **Random Forest Regressor**

- **Model Evaluation Metrics:**
  - **Root Mean Squared Error (RMSE)** for yield proxy predictions
  - **Deviation from Ground Truth** for soil measurement accuracy

---

## ⚙️ Evaluation Criteria

1. **Soil Measurement Evaluation:**
   - Submission via Gradio web interface
   - Evaluated based on deviation from ground truth (Max Score: 5)

2. **Yield Proxy Predictions:**
   - Assessed using **average RMSE** for biomass and plant height
   - Final scores scaled between 0 and 20

---

## 📂 Project Structure
```bash
├── data/
│   ├── train_data.csv
│   ├── test_data.csv
├── notebooks/
│   └── solution.ipynb
├── requirements.txt
├── README.md
```
---

## 💡 Key Accomplishments
- Developed an **ensemble ML model** achieving top accuracy
- Integrated ML model into an **interactive dashboard** for real-time predictions
- Reduced **RMSE** significantly compared to baseline models
- Awarded **1st Place** for innovative approach and model performance

---

## 🤝 Acknowledgments
- **NC Plant Sciences Initiative** for organizing the hackathon
- Support from mentors, team members, and contributors

Feel free to explore the code, datasets, and models! 🚀



