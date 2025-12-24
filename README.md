# 🇮🇩 Indonesia Food Price Forecasting (March 2026 Prediction)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Library](https://img.shields.io/badge/Library-Prophet%20%7C%20Pandas-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Executive Summary
Proyek ini bertujuan memprediksi lonjakan harga pangan (Studi Kasus: **Daging Ayam Ras**) menjelang momen Ramadhan & Idul Fitri **Maret 2026**. Menggunakan data historis PIHPS Nasional (2021-2025), model *Machine Learning* dikembangkan untuk mendeteksi pola musiman (*seasonality*).

## 📊 Key Findings
Berdasarkan analisis *Time Series Decomposition* menggunakan Facebook Prophet:
1.  **Trend Inflasi:** Terdapat tren kenaikan harga dasar daging ayam yang konsisten setiap tahun (Linear Growth).
2.  **Pola Musiman:** Terdeteksi lonjakan harga signifikan (*Seasonality Peak*) yang berulang setiap tahun di periode menjelang Hari Raya Idul Fitri.
3.  **Prediksi 2026:** Model memproyeksikan kenaikan harga mulai terjadi sejak awal tahun 2026, dengan estimasi harga mencapai range **Rp 37.000 - Rp 39.000** pada periode *festive season*.

## 🛠 Methodology
* **Data Source:** [https://data.badanpangan.go.id/datasetpublications/wk9/].
* **Data Cleaning:** Handling missing values, parsing format mata uang (IDR), dan standarisasi *time-series*.
* **Modeling:** Menggunakan algoritma **Facebook Prophet** dengan konfigurasi `yearly_seasonality=True` untuk menangkap pola tahunan yang kuat.

## 📈 Result Preview
*(Hasil visualisasi tren dan komponen musiman dari model)*
> *Lihat folder `notebooks/` untuk detail kode dan grafik lengkap.*

---
*Developed by Ryoga Elang Syailendra*
