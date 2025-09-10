# Titanic Dataset Visualization

Proyek ini berfokus pada eksplorasi dan visualisasi data **Titanic dataset** yang tersedia melalui `seaborn`. Analisis dilakukan untuk memahami distribusi data, mendeteksi missing values, serta mempelajari pola dari variabel-variabel utama seperti usia, kelas, jenis kelamin, hingga status keberlangsungan hidup penumpang.

## Langkah Utama Analisis

### 1. Eksplorasi Data Awal
- Menampilkan beberapa baris pertama (`head()`).
- Mengecek informasi kolom (`info()`).
- Menghitung jumlah missing values (`isna().sum()`).
- Melihat ringkasan statistik deskriptif (`describe()`).

### 2. Visualisasi Data Numerik
- **Boxplot** untuk semua kolom bertipe numerik → membantu mengidentifikasi distribusi nilai dan outlier.
- **Distribusi Fare dan Age** → menggunakan histogram & distplot untuk melihat sebaran biaya tiket dan usia penumpang.

### 3. Visualisasi Data Kategorikal
- **Distribusi Kelas Penumpang (`class` dan `pclass`)** → menggunakan histogram dan pie chart.
- **Embarked & Embark Town** → distribusi penumpang berdasarkan titik keberangkatan.
- **Who (man, woman, child)** → proporsi kategori penumpang.
- **Gender & Age** → violinplot untuk membandingkan distribusi usia berdasarkan jenis kelamin.
- **Gender & Survival** → violinplot untuk memvisualisasikan hubungan jenis kelamin dengan kemungkinan bertahan hidup.

### 4. Visualisasi Khusus
- **Pie Chart** pada beberapa variabel kategorikal (`embark_town`, `who`, `class`, `pclass`) → menunjukkan proporsi masing-masing kategori dengan persentase.

## Ringkasan Insight
- Distribusi usia penumpang bervariasi dengan mayoritas berada di rentang dewasa muda.  
- Fare memiliki distribusi yang skewed dengan outlier di harga tiket sangat tinggi.  
- Mayoritas penumpang berangkat dari **Southampton**.  
- Proporsi **laki-laki** lebih dominan dibanding perempuan dan anak-anak.  
- Perbedaan gender tampak signifikan dalam peluang bertahan hidup.  
- Kelas ekonomi (`class`/`pclass`) berpengaruh pada distribusi penumpang serta kaitannya dengan survival rate.  
