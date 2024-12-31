# Pemodelan Volatilitas Pasar Menggunakan Quaternion

Repositori ini berisi implementasi pemodelan volatilitas pasar modal dengan pendekatan **quaternion** untuk menganalisis hubungan multidimensi antara harga saham, sentimen pasar, dan faktor eksternal. Proyek ini memanfaatkan data historis saham dan alat visualisasi untuk memberikan wawasan baru tentang dinamika pasar.

## Fitur Utama
- **Pemodelan Quaternion**: Menggunakan quaternion untuk merepresentasikan variabel-variabel volatilitas seperti harga, sentimen, dan faktor eksternal.
- **Rotasi Quaternion**: Mengisolasi hubungan antar variabel dengan teknik rotasi quaternion.
- **Visualisasi Data**: Menyediakan grafik interaktif untuk analisis volatilitas, termasuk hubungan antara deviasi harga dan sentimen pasar.
- **Perbandingan Indikator Volatilitas**: Membandingkan hasil analisis dengan indikator volatilitas tradisional seperti ATR dan Bollinger Bands.

## Struktur Proyek
- `data/`: Folder yang berisi dataset historis yang digunakan dalam analisis.
- `notebooks/`: Notebook Jupyter untuk implementasi kode dan visualisasi.
- `scripts/`: Kode Python utama untuk pemrosesan data dan pemodelan quaternion.
- `results/`: Hasil grafik dan analisis dari eksperimen.

## Prasyarat
- Python 3.7 atau lebih baru
- Pandas
- NumPy
- Matplotlib
- PyQuaternion
- Scikit-learn
- Jupyter Notebook (opsional)

## Cara Menggunakan
1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/volatility-quaternion.git
   cd volatility-quaternion
