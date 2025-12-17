
# 📱 Smartphone Price Analysis & Prediction

## 📌 Project Overview
This project explores a dataset of smartphones to understand how technical specifications influence pricing.  

It includes an Exploratory Data Analysis (EDA) and the development of Machine Learning models to predict smartphone prices in **US Dollars (USD)**.

Prices were originally provided in Indian Rupees (INR) and converted to USD to ensure international consistency and avoid regional pricing distortions.

## 🎯 Objectives
- Perform exploratory analysis of smartphone specifications (RAM, battery, display, processor, camera)

- Identify the most important features influencing smartphone prices

- Build and evaluate regression models to predict smartphone prices

- Compare a baseline linear model with a non-linear ensemble model

## 🛠️ Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Project Structure

```text
smartphones-project/
├── data/
│   └── smartphones.csv
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_model.ipynb
│   └── 03_price_segmentation_and_recommendations.ipynb
├── README.md
├── requirements.txt
```

## 🚀 How to Run
1. Clone this repository  
2. Create and activate a virtual environment  
3. Install dependencies using `requirements.txt`  
4. Run the notebooks in order:
   - `01_eda.ipynb`
   - `02_model.ipynb`
   - `03_price_segmentation_and_recommendations.ipynb`

---

## 🤖 Modeling & Results
Two regression models were trained to predict smartphone prices (USD):

- **Random Forest Regressor**
- **Linear Regression (baseline)**

### 📊 Model Performance (MAE)
- **Random Forest:** ~ **$45 USD**
- **Linear Regression:** ~ **$95 USD**

The Random Forest model significantly outperformed the linear baseline, demonstrating its ability to capture non-linear relationships between smartphone specifications and price.

---

## 🔍 Feature Importance
The most influential features in pricing were:
- CPU clock speed
- User rating
- Display size
- Battery capacity
- Storage

This aligns well with real-world expectations of smartphone pricing.

---

## 📌 Key Takeaways
- Smartphone pricing is strongly driven by performance-related features
- Non-linear models perform substantially better than linear baselines
- Proper price normalization (INR → USD) is essential for global analysis

---

## 📈 Future Improvements
- Hyperparameter tuning
- Price segmentation and recommendation analysis
- Inclusion of brand-level effects
- Model explainability using SHAP

---

## 👤 Author
**Jefferson Gomes**  
Data Analyst / Data Scientist
