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
- Jumlah **total tower** sedikit
- Tarif ongkir **REGULER** tinggi

### 📈 Rumus Skor Prioritas

```python
prioritas_score = REGULER / total_tower
```


### 📁 Output

- `HASIL_ANALISIS_BEKASI.xlsx` – Hasil lengkap analisis yang sudah digabung dan dibersihkan
- `REKOMENDASI_PRIORITAS_SINYAL.xlsx` – Top 10 kecamatan yang direkomendasikan untuk penguatan jaringan

### 🧠 Insight Sementara

- Beberapa kecamatan yang secara geografis berada di pinggiran cenderung memiliki jumlah tower sedikit namun ongkir tinggi.
- Korelasi antara jumlah infrastruktur dan efisiensi ongkir dapat menjadi dasar perencanaan pembangunan jaringan telekomunikasi yang lebih merata.


### ⚠️ Disclaimer

Data yang digunakan bersifat dummy dan hanya digunakan untuk keperluan pembelajaran dan simulasi analisis data. Hasil tidak mewakili kondisi riil Kabupaten Bekasi.

👤 Author
- Nama: Lury Lukmanawati
- GitHub: https://github.com/blueonsky29
- Email: lurylukmanawati@gmail.com


