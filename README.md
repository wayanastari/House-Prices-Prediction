**House Prices - Advanced Regression Techniques**

Prediksi harga rumah menggunakan **Stacking Regressor** dengan kombinasi model Ridge, XGBoost, dan LightGBM.  
Project ini dibuat untuk mengikuti kompetisi https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques 

📌 Deskripsi Proyek
Tujuan proyek ini adalah membangun model prediksi harga rumah yang akurat dengan memanfaatkan:
- **Feature Engineering** untuk meningkatkan kualitas data.
- **Model Baseline** sebagai titik pembanding.
- **Stacking Regressor** untuk menggabungkan kekuatan beberapa algoritma.
- **Evaluasi Model** dengan metrik R² dan RMSE.

📊 Dataset
Dataset diambil dari Kaggle:
- **Train Data:** Berisi fitur properti dan harga rumah.
- **Test Data:** Berisi fitur properti tanpa harga rumah (untuk diprediksi).
- **Target:** `SalePrice`
📎 Link Dataset: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

⚙️ Metode & Model
1. Baseline Model
   **Ridge** digunakan sebagai pembanding awal.
2. Stacking Regressor
  Menggabungkan tiga model:
- Ridge Regression
- XGBoost Regressor
- LightGBM Regressor

🏆 Kaggle Score
R² Validation: 0.9115
RMSE Validation: 0.1285
Kaggle Public Leaderboard: 0.12937 V3
