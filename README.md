# 📡 Analisis Infrastruktur Tower & Ongkir JNE – Kabupaten Bekasi

Proyek ini bertujuan untuk menganalisis **hubungan antara jumlah menara telekomunikasi (2G, 3G, 4G)** dan **tarif pengiriman JNE (REGULER, OKE, YES)** di berbagai kecamatan di Kabupaten Bekasi.

## 📊 Dataset
Terdiri dari dua data dummy:
1. `KEC KAB BEKASI_DATA DUMMY.xlsx` – berisi nama kecamatan, jumlah tower 2G/3G/4G, dan koordinat lokasi.
2. `ONGKIR.xlsx` – berisi ongkos kirim layanan JNE untuk tiap kecamatan.

## ⚙️ Tools yang Digunakan
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## 🔍 Analisis yang Dilakukan
- Pembersihan dan normalisasi data kecamatan
- Konversi format koordinat `1070163` → `107.0163`
- Penggabungan data tower & ongkir berdasarkan kecamatan
- Visualisasi sebaran tower per teknologi
- Korelasi antara jumlah tower dan tarif pengiriman
- Pemetaan lokasi tower berdasarkan koordinat
- Identifikasi 10 kecamatan prioritas yang membutuhkan penguatan sinyal

## 📍 Rekomendasi Wilayah Prioritas
Kecamatan dengan:
- Jumlah total tower sedikit
- Tarif ongkir REGULER tinggi

Skor dihitung dengan rumus sederhana:
