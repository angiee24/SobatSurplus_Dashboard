# sobatsurplus_dashboard

# FoodRescue Samarinda - Explanatory Analysis Dashboard

Dashboard interaktif ini dibangun menggunakan framework **Streamlit** untuk menyajikan analisis eksplanatori (*explanatory analysis*) terkait optimalisasi logistik dan penyelamatan surplus makanan perkotaan di wilayah Kota Samarinda. Proyek ini berfokus pada visualisasi performa lapangan, mitigasi risiko limbah, serta validasi ilmiah efisiensi sistem baru.

## Fitur Utama Dashboard
* **Ringkasan Metrik Strategis (KPI):** Pemantauan volume total pangan yang diselamatkan, rasio keberhasilan penjemputan, indeks urgensi, serta estimasi riil reduksi emisi karbon ($CO_2$).
* **Logistik & Efisiensi Jarak:** Analisis komparatif jarak tempuh spasial terhadap status keberhasilan operasional kurir relawan.
* **Pola Risiko & Karakteristik Komoditas:** Identifikasi tingkat kerentanan pangan (*waste risk*) berdasarkan jenis makanan dan kontribusi ekosistem donatur sektoral (Hotel, Supermarket, dan Restaurant).
* **Validasi Performa Sistem (A/B Testing):** Pembuktian statistik menggunakan independen T-Test untuk memvalidasi efisiensi waktu fitur berbasis lokasi (LBS) platform FoodRescue dibandingkan metode manual konvensional.

## Teknologi & Library Yang Digunakan
* **Python** (Bahasa Pemrograman Utama)
* **Streamlit** (Framework Web Dashboard)
* **Pandas & NumPy** (Manipulasi dan Pipeline Data)
* **Matplotlib & Seaborn** (Kustomisasi Visualisasi Data Bertema Muted Sage Green)
* **SciPy (stats)** (Komputasi Uji Hipotesis Statistik T-Test)

## Struktur File Utama
* `dashboard.py`: Kode murni arsitektur antarmuka dan logika visualisasi dashboard.
* `foodrescue_feature_engineering_fix.csv`: Dataset operasional yang telah melalui tahap rekayasa fitur (*feature engineering*).

## Cara Menjalankan Dashboard di Lokal
1. Pastikan semua library yang dibutuhkan telah terinstal.
2. Jalankan perintah berikut pada terminal atau command prompt di dalam direktori proyek:
   ```bash
   streamlit run dashboard.py

### Cara Memasukkannya Lewat Git Bash:
Jika kamu ingin langsung memperbarui file `README.md` tersebut dari Git Bash, jalankan perintah ini (bisa dicopas):

1. Buka file `README.md` di teks editor laptopmu, lalu *paste* teks markdown di atas dan simpan.
2. Jalankan perintah Git berikut untuk meng-upload perubahannya:
```bash
git add README.md
git commit -m "update README documentation"
git push origin main --force
