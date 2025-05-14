# Python_EDA_AnxietyDepression

## Project Portfolio Exploratory Data Analysis

EDA atau Explanatory Data Analysis ini bertujuan untuk mengeksplorasi data dan menghasilkan informasi-informasi penting. 

## Workflow

### 1. Business Understanding
Data yang saya gunakan merupakan data Anxiety Depression yang berasal dari Kaggle.com. Dataset ini berisi tentang beberapa hal yang berkaitan dengan kecemasan, depresi, dan pengaruh kesehatan mental. Berikut adalah tautan untuk mengaksesnya: https://www.kaggle.com/datasets/ak0212/anxiety-and-depression-mental-health-factors/data 
Dataset ini berjumlah 1200 data dan 21 fitur yang dibagi menjadi 5 kategori fitur. 5 fitur bertipe data object, 13 data bertipe integer, dan 2 data bertipe float.
 Berikut merupakan fitur yang tedapat pada data tersebut :
Fitur yang berkaitan dengan demografi : 
- Usia
- Jenis Kelamin
- Pendidikan
- Status Pekerjaan
- 
Fitur yang berkaitan dengan gaya hidup :   
- Jam tidur,
- Akktivitas Fisik
- Social support  = dukungan Sosial

Fitur yang dilakukan sebagai metrik pengukuran :
- Skor kecemasan
- Skor depresi
- tingkat stres

Fitur yang berkaitan dengan riwayat medis :
- Riwayat keluarga memiliki penyakit mental
- Penyakit Kronis
- Penggunaan Obat

Fitur penanganan :
- Terapi
- Meditasi
- Penggunaan zat

Fitur faktor tambahan :
- Stres finansial
- Stres Kerja
- Harga Diri
- Kepuasan Hidup
- Kesepian


   
### 2. Data Preparation
- Melakukan pengecekan statistik deksriptif dataset
- Melakukan pengecekan tipe data dan informasi dataset
- Mengidentifikasi jumlah nilai yang hilang
- Mengidentifikasi jumlah data yang duplikat
- Mengidentifikasi fitur data yang mengalami outlier

Hasil pengecakan menunjukkan hasil sebagai berikut:
- 5 kolom yang bertipe data object, diubah menjadi numerik menggunakan library label encoding
- Tipe data float64 berjumlah 2 pada kolom sleep_hours and physical_activity_hrs,tipe data integer pada 14 kolom, dan tipe data object terdapat pada 5 kolom.
- Didapatkan data yang missing value terdapat pada  fitur ‘Medication_use’ dan ‘Substance_use’ , kolom tersebut bertipe data object. Untuk mengatasi missing value tersebut menggunakan mode atau modus dari masing--masing kolom.
- Tidak ditemukan data yang du[;ikat pada dataset ini
- Didapatkan 6 fitur yang outlier, yaitu fitur gender, Sleep_Hours, Physical_Activity_Hrs, Medication_Use, Therapy, dan Substance_Use


### 3. Data Cleaned


### 4. Analisis dan Visualisasi



## Insight  :
1. Hubungan tingkat pendidikan dengan tingkat stres :
Terdapat perbedaan rata-rata stres antar kelompok pendidikan.
TIngkat pendidikan yang lebih rendah(SMA/SMK) memiliki tingkat stres yang lebih tinggi dibandingkan Sarjana dan Doktor(PHD)
2. Hubungan status pekerjaan dengan tingkat stres:
Perbedaan signifikan juga terlihat antar kelompok pekerjaan.
Tingkat stres tertinggi pada responden yang tidak bekerja dan tingkat stres terendah pada responden yang sudah pensiun.
3. Dari 20 fitur X, visualissi diatas menunjukkan fitur yang paling berpengaruh dalam Anxiety dan Depresi adalah fitur family_history_mental_illnes.





#PYTHON #EDA #DATA-ANALYTICS #DATA-SCIENCE
