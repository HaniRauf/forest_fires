# 🔥 Forest Fire Area Prediction (Portugal)

## 🔍 Project Overview
This project analyzes the **Forest Fires dataset** from the UCI Machine Learning Repository. It explores how meteorological and fire weather indices affect the burned area of forest fires in the northeast region of Portugal. The main objective is to build a predictive regression model using key weather variables to estimate the log-transformed burned area, which helps mitigate data skew and improve model performance.

---

## 📁 Dataset
**Source**: UCI Machine Learning Repository – [Forest Fires Dataset](https://archive.ics.uci.edu/ml/datasets/forest+fires)  
**Description**: The dataset contains 517 observations with 12 features, including:
- **Meteorological Data**: temperature, relative humidity, wind, rain  
- **Fire Weather Indices**: FFMC, DMC, DC, ISI  
- **Target Variable**: `area` – the burned area in hectares (log-transformed in this analysis)

---

## 📁 Files in the Repository
- 📓 `forest_fires.ipynb` – Jupyter Notebook with data analysis, visualization, feature engineering, and regression modeling  
- 📄 `forestfires.csv` – Dataset used for training the model (can be downloaded from the UCI link above)

---

## 🛠️ Tools & Libraries Used
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- Jupyter Notebook  

---

## 🧪 Features & Analysis Performed
- Loaded and explored dataset  
- Performed log transformation on skewed `area` variable  
- Checked correlations among fire indices and weather variables  
- Selected top features influencing burned area  
- Split data into training and testing sets  
- Trained a **Linear Regression** model on selected features  
- Evaluated model using standard regression metrics:
  - **R² Score**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**

---

## 📊 Sample Visualizations
- 🔥 Scatter Plot – Wind vs. Burned Area  
- 🧯 3D Surface Plot – Temperature 

---

## 🧠 Machine Learning Model
- **Model Used**: Linear Regression  
- **Target Variable**: `log(area + 1)` – to normalize right-skewed data  
- **Top Features Used**: temp, RH, wind, rain, FFMC, DMC, DC, ISI  
- **Performance Metrics**: Displayed in notebook (example: RMSE, R²)

---

## 🏁 How to Run
1. Clone the repository or download the notebook and dataset  
2. Open `forest_fires.ipynb` in **Jupyter Notebook** or **Google Colab**  
3. Ensure all required libraries are installed  
4. Run cells in order to view data analysis and predictions  

---

## 👩‍💻 Author
**Hani Bint E Rauf** – Master’s in Data Science  
📧 Email: hanibinterauf@gmail.com  
🛠️ Fiverr: [fiverr.com/hani_binte_rauf](https://fiverr.com/hani_binte_rauf)
