Based on the **Capstone Project Guidelines.pdf** and your mobile price prediction project, here's a professional and informative `README.md` file you can use for your GitHub repository named **DSA-ML Capstone - Mobile Price Prediction.

---

### 📄 README.md

# DSA-ML Capstone - Mobile Price Prediction

This is the final capstone project for my Data Science and Machine Learning course. The goal of this project is to predict the price range of mobile devices using various hardware and feature attributes like battery power, RAM, screen size, camera quality, and more.

---

## 📌 Problem Statement

Given a dataset containing features of mobile phones (e.g., battery power, RAM, internal memory, etc.), the task is to build a classification model that predicts the price range of the phone, categorized into 4 classes:
- 0: Low Cost
- 1: Medium Cost
- 2: High Cost
- 3: Very High Cost

---

## 🧾 Dataset

The dataset used in this project is `mobile_data.csv`, which contains **21 features** and **1 target variable (`price_range`).

### 🔢 Features:

| Feature        | Description                              |
|----------------|------------------------------------------|
| battery_power  | Battery power in mAh                     |
| blue           | Has Bluetooth (1 = yes, 0 = no)          |
| clock_speed    | CPU clock speed in GHz                   |
| dual_sim       | Dual SIM support (1 = yes, 0 = no)       |
| fc             | Front camera mega pixels                 |
| four_g         | Has 4G (1 = yes, 0 = no)                 |
| int_memory     | Internal memory in GB                    |
| m_dep          | Mobile depth in cm                       |
| mobile_wt      | Weight of mobile                         |
| n_cores        | Number of cores                          |
| pc             | Primary camera mega pixels               |
| px_height      | Pixel resolution height                  |
| px_width       | Pixel resolution width                   |
| ram            | RAM in MB                                |
| sc_h           | Screen height                            |
| sc_w           | Screen width                             |
| talk_time      | Talk time in hours                       |
| three_g        | Has 3G (1 = yes, 0 = no)                 |
| touch_screen   | Has touch screen (1 = yes, 0 = no)       |
| wifi           | Has Wi-Fi (1 = yes, 0 = no)              |
| price_range    | Target variable (Price range class)        |


## 🛠️ Tools & Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Tasks Completed

✅ Data Preprocessing  
✅ Exploratory Data Analysis (EDA)  
✅ Feature Engineering (e.g., feature selection using SelectKBest)  
✅ Model Building (Random Forest, XGBoost, etc.)  
✅ Model Evaluation (Accuracy, Confusion Matrix, Classification Report)  
✅ Optional: Web Deployment using **Streamlit**

