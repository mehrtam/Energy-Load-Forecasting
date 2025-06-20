# **Energy Load Forecasting Using AI**

## **🔹 Project Overview**
This project focuses on forecasting energy consumption using machine learning techniques. The model utilizes historical real-world power consumption data from **Iran’s National Power Grid** (from **March 22, 2019 – February 9, 2023**) with hourly temperature records. The goal is to develop an accurate forecasting model and compare predictions with actual consumption data for the final 40 days of 2022.

---

## **📌 Features**
- ✅ **Processed 34,000 hourly-labeled samples** of real-world energy consumption data.
- ✅ **Engineered features**, ensuring a minimum of **20 derived features (including up to the 20th-order differentials)** for improved forecasting.
- ✅ **Designed & trained ML models**, using **20-30% of the dataset** for training to enhance model generalization.
- ✅ **Developed a time-series forecasting model** to predict **energy demand for the last 40 days of 2022 (24×40 hourly predictions).**
- ✅ **Evaluated model performance** by comparing forecasted vs. actual energy consumption values.

---

## **🛠️ Technologies & Tools Used**
- **Programming Language:** Python
- **Machine Learning Libraries:** Scikit-Learn, TensorFlow, XGBoost
- **Data Processing:** Pandas, NumPy, Matplotlib
- **Time-Series Forecasting Models:** ARIMA, LSTMs, XGBoost
- **Deployment:** Google Colab, Jupyter Notebook

---

## **📂 Project Structure**
```bash
├── data/                   # Dataset files (Confidential)
├── notebooks/              # Jupyter Notebooks for model training & evaluation
├── models/                 # Trained machine learning models
├── scripts/                # Python scripts for data processing & visualization
├── README.md               # Project documentation
```

---

## **🚀 How to Run the Project**
1. **Ensure you have the dataset** (Confidential and not for external sharing).
2. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Energy-Load-Forecasting.git
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the main forecasting script:**
   ```bash
   python main.py
   ```

---

## **📊 Results & Performance**
- Forecasted energy demand for the **last 40 days of 2022**.
- Evaluated the model’s **accuracy & efficiency** using **MSE, RMSE, and R² Score**.
- Visualized actual vs. predicted consumption trends for performance assessment.

---

## **📬 Contact**
For any questions or collaborations, reach out to:
- **Name:** Mehrta Eslami
- **Email:** mehrtaeslamii@gmail.com

---

