# 🛒 Walmart Sales Forecasting (Time Series Analysis)

## 📌 Business Overview
Proyek ini bertujuan untuk memprediksi penjualan mingguan di berbagai departemen toko Walmart. Prediksi yang akurat membantu perusahaan dalam manajemen inventaris, pengaturan staf, dan strategi promosi.

## 📊 Dataset
Data berasal dari [Kaggle Walmart Dataset]. Variabel utama meliputi:
* **Store & Dept**: Identitas toko dan departemen.
* **Weekly_Sales**: Target prediksi.
* **IsHoliday**: Penanda apakah minggu tersebut terdapat hari libur besar.
* **Features**: Temperature, Fuel_Price, CPI, dan Unemployment.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Statsmodels (untuk SARIMAX/Prophet).

## 🚀 Workflow
1. **Exploratory Data Analysis (EDA):** Menganalisis pola musiman (seasonality) saat hari raya seperti Thanksgiving dan Natal.
2. **Data Preprocessing:** Menangani missing values dan melakukan feature engineering (ekstraksi tanggal).
3. **Modeling:** Membandingkan model Random Forest Regressor dan XGBoost.
4. **Evaluation:** Menggunakan metrik WMAE (Weighted Mean Absolute Error) sesuai standar kompetisi Walmart.

## 📈 Key Insights
* Penjualan melonjak drastis pada minggu Thanksgiving dan Natal.
* Faktor pengangguran (Unemployment) memiliki korelasi negatif terhadap daya beli di beberapa wilayah tertentu.

## 📁 Repository Structure
* `notebooks/`: File .ipynb proses analisis.
* `data/`: Link sumber data.
* `models/`: File model yang sudah dilatih (optional).
