# Analisis Historis Emisi CO₂ per Kapita di Seluruh Dunia

## 🎯 Tujuan Proyek

Studi ini bertujuan untuk memahami dinamika emisi karbon dioksida (CO₂) per kapita secara global dalam jangka panjang. Fokusnya adalah pada pola tren di berbagai negara, identifikasi negara-negara dengan kontribusi tertinggi maupun terendah, serta kemungkinan kaitannya dengan pertumbuhan ekonomi dan demografi.

## 🧠 Latar Belakang

Dalam beberapa dekade terakhir, emisi karbon menjadi isu sentral dalam diskusi perubahan iklim global. CO₂ adalah gas rumah kaca utama yang dihasilkan dari pembakaran bahan bakar fosil, proses industri, dan aktivitas manusia lainnya. Tren emisi per kapita antarnegara menunjukkan variasi signifikan, tergantung pada tingkat pembangunan, bauran energi, dan kebijakan lingkungan.

Dengan menganalisis data emisi per kapita dari seluruh dunia, kita dapat memperoleh pemahaman yang lebih luas mengenai perbedaan kontribusi emisi dan efektivitas strategi pengurangannya di berbagai konteks negara.

## 🗃️ Sumber Data

- Data emisi CO₂ per kapita (indikator: `EN.ATM.CO2E.PC`)
- Sumber: [World Bank Open Data](https://data.worldbank.org/indicator/EN.ATM.CO2E.PC)
- Cakupan waktu: 1960–2022
- Satuan: Metrik ton per kapita per tahun

## 🛠️ Metodologi Analisis

1. **Pengumpulan Data**: Mengambil data global dari World Bank dalam format CSV.
2. **Praproses**: Pembersihan dan restrukturisasi data untuk seluruh negara.
3. **Eksplorasi Data**: Melihat tren global, perbandingan antarnegara, dan deteksi outlier.
4. **Analisis Lanjutan**: Korelasi dengan GDP per kapita, status pembangunan, dan regional.
5. **Visualisasi**: Menyajikan data dalam bentuk grafik tren, heatmap, dan peringkat negara.

## 📊 Hasil Visualisasi

- **Peta Dunia Emisi**: Visualisasi peta global berdasarkan emisi per kapita.
- **Grafik Tren Negara Tertentu**: Amerika Serikat, Tiongkok, Indonesia, Norwegia, India, dan lainnya.
- **Perbandingan Regional**: ASEAN vs OECD vs Sub-Sahara Afrika.
- **Korelasi Emisi dan GDP**: Tren umum bahwa negara maju memiliki emisi per kapita lebih tinggi.

## 📌 Insight Utama

- Negara-negara industri memiliki jejak emisi per kapita yang jauh lebih tinggi dibandingkan negara berkembang.
- Tren di negara-negara maju mulai menunjukkan stabilisasi atau penurunan emisi.
- Negara berkembang cenderung mengalami peningkatan seiring pertumbuhan ekonomi dan urbanisasi.

## ✍️ Kesimpulan

Analisis lintas negara ini mengungkapkan betapa berbedanya dinamika emisi per kapita antar wilayah. Upaya pengurangan emisi perlu mempertimbangkan tanggung jawab historis, kapasitas nasional, serta potensi dukungan internasional. Analisis data global seperti ini bisa menjadi pijakan dalam menyusun kebijakan kolaboratif dan adil dalam menghadapi krisis iklim.

## 📁 Struktur Folder

```
project-root/
├── data/
│   └── co2_per_capita_world.csv
├── image/
│   └── co2_per_capita_world.csv
├── notebooks/
│   └── analisis_emisi_global.ipynb
├── output/
│   └── peta_dunia_emisi.png
└── README.md
```

## 🧰 Tools dan Library

- `pandas`: untuk pemrosesan data
- `matplotlib` & `seaborn`: untuk visualisasi grafik
- `plotly` atau `folium`: untuk visualisasi interaktif dan peta dunia
- `numpy`: untuk analisis numerik tambahan

## 🚀 Pengembangan Lanjutan

- Menambahkan data energi terbarukan dan konsumsi energi nasional
- Integrasi dengan data populasi dan urbanisasi
- Model proyeksi emisi hingga 2050 menggunakan metode statistik atau machine learning

## 🌍 Penutup

Dengan memahami data emisi CO₂ per kapita secara global, kita bisa mendorong diskusi yang lebih adil dan ilmiah dalam mengatasi perubahan iklim. Data bukan hanya alat, tetapi jembatan menuju kebijakan yang lebih tangguh, kolaboratif, dan berbasis bukti.

**Satu Data, Banyak Negara, Satu Tujuan untuk Iklim Lebih Baik.**
