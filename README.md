# Implementasi Multivariate Regression dan Clustering Analysis

## Penilaian Kapabilitas Intelligence & Emotional Quotient (IQ–EQ) Generasi Alpha

### dalam Mendukung Visi Indonesia Emas 2045

---

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk **menganalisis kapabilitas Intelligence Quotient (IQ) dan Emotional Quotient (EQ) Generasi Alpha** sebagai fondasi pembangunan **Sumber Daya Manusia (SDM) unggul** dalam rangka mewujudkan **Visi Indonesia Emas 2045**.

Penelitian ini mengadopsi pendekatan **statistik multivariat** dan **clustering analysis** untuk:

* Mengkaji hubungan antara IQ dan EQ,
* Mengidentifikasi faktor-faktor eksternal yang memengaruhi keduanya secara simultan,
* Mengelompokkan anak-anak Generasi Alpha berdasarkan profil kapabilitas yang terbentuk.

Proyek ini dikembangkan dalam konteks **kompetisi/statistik akademik** oleh **Tim Madep Mantep – Politeknik Statistika STIS**.

---

## 🎯 Tujuan Penelitian

1. Mengidentifikasi korelasi antara variabel dependen yang merepresentasikan **IQ dan EQ**.
2. Menganalisis pengaruh faktor eksternal terhadap IQ dan EQ menggunakan **multivariate regression analysis**.
3. Mengelompokkan responden berdasarkan variabel signifikan yang memengaruhi IQ dan EQ dengan **clustering analysis**.

---

## 🧠 Metodologi

Penelitian dilakukan melalui tiga tahapan utama:

### 1️⃣ Analisis Korelasi

* Korelasi Pearson antara IQ dan EQ
* Visualisasi scatter plot dan heatmap
* Uji signifikansi menggunakan **Bartlett’s Sphericity Test**

### 2️⃣ Multivariate Regression Analysis

* Model regresi multivariat dengan dua variabel dependen (IQ & EQ)
* Pengujian asumsi:

  * Normalitas multivariat (Chi-square plot & Jarque-Bera)
  * Multikolinearitas (VIF)
  * Normalitas residual, homoskedastisitas, dan non-autokorelasi
* Uji signifikansi:

  * Wilks’ Lambda
  * Uji F dan uji T
* Evaluasi model:

  * Koefisien determinasi (R²)
  * Eta-squared lambda (η²)

### 3️⃣ Clustering Analysis

* Clustering pada variabel signifikan secara multivariat
* Penanganan **data campuran (numerik & kategorik)** menggunakan:

  * K-Prototypes
  * Adaptive K-Means (AD K-Means)
  * K-Medoids (Gower Distance)
* Penentuan jumlah klaster optimal:

  * Elbow Method
  * Calinski–Harabasz Index
* Evaluasi klaster:

  * Silhouette Score
  * Davies–Bouldin Index
  * Calinski–Harabasz Index

---

## 📊 Data dan Variabel

### Sumber Data

* **Survei Kapabilitas Generasi Emas (SKGE)**
* Sampel: **100 anak Generasi Alpha**
* Tipe data: **cross-sectional**

### Variabel Dependen

* **Skor_Kognitif_Terstandarisasi (IQ)** – skala 0–100
* **Indeks_Kematangan_Karakter (EQ)** – skala 0–100

### Variabel Independen

* Pajanan_Teknologi_Pendidikan (numerik)
* Partisipasi_Seni_Olahraga (kategorik/dummy)
* Indeks_Gizi_Seimbang (numerik)
* Kualitas_Interaksi_OrangTua (numerik)
* Iklim_Belajar_Sekolah (numerik)

---

## 📈 Hasil Utama

### 🔹 Korelasi IQ–EQ

* Koefisien korelasi Pearson: **0,65**
* Hubungan positif kuat dan signifikan (p-value < 0,05)

### 🔹 Regresi Multivariat

* Model signifikan secara simultan (Wilks’ Lambda p-value = 0,0152)
* R² IQ = **68,44%**
* R² EQ = **56,90%**
* Eta-squared lambda (η²) = **87,35%**

### 🔹 Clustering

* Jumlah klaster optimal: **2 klaster**
* Algoritma terbaik: **Adaptive K-Means**
* Perbedaan utama klaster:

  * Paparan teknologi pendidikan
  * Iklim belajar sekolah
  * Partisipasi seni dan olahraga

---

## 🧩 Interpretasi Klaster

* **Klaster 0**: Paparan teknologi tinggi, iklim belajar kondusif, partisipasi seni/olahraga aktif
* **Klaster 1**: Paparan teknologi rendah, iklim belajar kurang optimal

Klasterisasi ini memberikan dasar segmentasi kebijakan pendidikan yang lebih tepat sasaran.

---

## 🚀 Tools & Teknologi

* **Python 3** (Google Colab)
* **R** (analisis multivariat)
* Library utama:

  * pandas, numpy
  * scikit-learn
  * scipy
  * statsmodels
  * cluster, factoextra (R)

---

## 👥 Tim

**Tim Madep Mantep – Politeknik Statistika STIS**

* Dutatama Rosewika T. H. (Ketua)
* Suhendra Widi Prayoga (Anggota)

---

## 📜 Lisensi

Proyek ini disusun untuk **Olimpiade Statistika SMATIC UNJ 6.0 2025**.
Tidak digunakan untuk tujuan komersial.

---

## 📸 Foto Kegiatan

Lampiran foto kegiatan sebagai berikut

<table>
  <tr>
    <td align="center">
      <img src="Dokumentasi%201.jpg" alt="Dokumentasi 1" width="300" />
      <br/>
      <strong>Dokumentasi 1</strong>
    </td>
    <td align="center">
      <img src="Dokumentasi%202.jpg" alt="Dokumentasi 2" width="300" />
      <br/>
      <strong>Dokumentasi 2</strong>
    </td>
    <td align="center">
      <img src="Dokumentasi%203.jpg" alt="Dokumentasi 3" width="300" />
      <br/>
      <strong>Dokumentasi 3</strong>
    </td>
  </tr>
</table>

> *“Dengan data dan analisis cerdas, kita tidak sekadar mengukur kapasitas, tetapi merancang masa depan yang berkualitas.”* 
