# Forecasting Jumlah Transaksi Harian

Proyek ini merupakan bagian dari tugas akhir untuk topik Forecasting dalam bootcamp Data Science. Tujuan utama proyek ini adalah untuk memodelkan dan memprediksi jumlah transaksi harian menggunakan dua metode time series: **SARIMA** dan **ETS**.

## 📁 Struktur Proyek

- `A_DEC7_Forecasting_DS33A_Oktavindy.ipynb` : Notebook utama yang berisi proses EDA, modelling, evaluasi model, dan prediksi.
- `data/` : (Opsional) Folder yang menyimpan dataset mentah.
- `output/` : (Opsional) Folder berisi hasil forecasting dan visualisasi (jika disimpan sebagai file).
- `requirements.txt` : Daftar library yang digunakan.

## 🔍 Metodologi

1. **Exploratory Data Analysis (EDA)** untuk melihat pola tren musiman dan outlier.
2. **Pemodelan Time Series** menggunakan:
   - SARIMA (Seasonal ARIMA)
   - ETS (Error-Trend-Seasonal)
3. **Evaluasi Model** berdasarkan nilai **MAPE** dan visualisasi prediksi.
4. **Forecasting** jumlah transaksi untuk bulan Januari 2020.

## ✅ Hasil Evaluasi

| Model  | MAPE (%) |
|--------|-----------|
| SARIMA | 6.73      |
| ETS    | **5.04**  |

Model **ETS** dipilih sebagai model terbaik untuk memprediksi transaksi di Januari 2020.

## 🚀 Cara Menjalankan

1. Clone repo:
git clone https://github.com/username/forecasting-transaksi.git
cd forecasting-transaksi

2. (Opsional) Install library:
pip install -r requirements.txt

3. Buka dan jalankan notebook:
jupyter notebook A_DEC7_Forecasting_DS33A_Oktavindy.ipynb


## ⚠️ Catatan
Dataset tidak disertakan dalam repositori ini karena bersifat internal. Silakan sesuaikan path dataset pada bagian awal notebook.




