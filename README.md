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


## Visualization key
*<img width="575" height="245" alt="image" src="https://github.com/user-attachments/assets/748946a4-d107-4e31-8c50-79372e338f16" />
*<img width="1138" height="481" alt="image" src="https://github.com/user-attachments/assets/b46094ac-efe9-4a89-9c3e-18745e3052ec" />
*<img width="1141" height="482" alt="image" src="https://github.com/user-attachments/assets/6db0990b-8228-4273-bc84-f2d1624617d3" />
* <img width="1148" height="921" alt="image" src="https://github.com/user-attachments/assets/488d1658-0545-43cf-b9e7-bc32370d5141" />
* <img width="1144" height="518" alt="image" src="https://github.com/user-attachments/assets/f003975a-98d8-401b-b2de-6cf494d93cb5" />


* 
