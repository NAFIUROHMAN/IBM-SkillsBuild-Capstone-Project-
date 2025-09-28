# Capstone Project IBM SkillsBuild

**Analisis Hubungan Kondisi Fisiologis dan Psikologis**

---

## 📌 Latar Belakang

Kesehatan mental dan fisik merupakan dua aspek yang saling berkaitan erat. Berbagai penelitian menunjukkan bahwa kondisi fisiologis—seperti detak jantung, variasi detak jantung (HRV), aktivitas otak (EEG), tekanan darah, kadar oksigen, maupun respons galvanik kulit (GSR)—dapat memberikan gambaran mengenai keadaan psikologis seseorang, misalnya tingkat stres, mood, fokus, atau beban kognitif.

Pemahaman hubungan ini dapat dimanfaatkan untuk:

* **Pemantauan kesehatan mental** berbasis sensor fisiologis.
* **Pengembangan sistem pendukung keputusan** di bidang kesehatan.
* **Aplikasi interaktif** seperti chatbot yang dapat merespons kondisi psikologis pengguna.

Proyek ini merupakan bagian dari **Capstone Project IBM SkillsBuild**, yang bertujuan untuk menerapkan analisis data serta pengembangan model machine learning dalam konteks nyata.

---

## 📊 Dataset yang Digunakan

Dataset yang digunakan dalam proyek ini diperoleh dari sumber terbuka di internet, berisi data fisiologis dan label psikologis. Variabel yang tercatat antara lain:

* **Fisiologis**: HR, HRV, EEG, GSR, tekanan darah, saturasi oksigen, dll.
* **Psikologis**: mood, tingkat stres, fokus, beban kognitif, dll.

Dataset ini memungkinkan eksplorasi korelasi serta pemodelan prediktif antara dua domain tersebut.

---

## ⚙️ Metodologi Analisis

Langkah-langkah yang dilakukan dalam proyek ini:

1. **Data Collection & Preprocessing**

   * Pembersihan data (handling missing values, normalisasi).
   * Feature engineering pada sinyal fisiologis.

2. **Eksplorasi Data (EDA)**

   * Analisis distribusi variabel.
   * Korelasi antara indikator fisiologis dan psikologis.

3. **Modeling**

   * Menggunakan algoritma machine learning (mis. Random Forest, SVM, atau Neural Network).
   * Evaluasi dengan metrik akurasi, precision, recall, F1-score.

4. **Deployment**

   * Membuat **chatbot sederhana** yang mampu memberikan respon/insight berdasarkan data psikologis yang diprediksi dari input fisiologis.

---

## 🚀 Hasil dan Insight

* Ditemukan adanya **hubungan signifikan** antara HRV dan tingkat stres, serta antara pola EEG dengan tingkat fokus.
* Model machine learning mampu **memprediksi kondisi psikologis** dengan akurasi yang cukup baik (detail metrik disesuaikan dengan hasil eksperimen).
* Implementasi sederhana berupa **chatbot berbasis data** dibuat untuk mendemonstrasikan aplikasi praktis dari analisis ini.

---

## ✅ Kesimpulan

* Data fisiologis dapat dijadikan indikator yang cukup andal untuk memprediksi keadaan psikologis seseorang.
* Analisis ini membuka peluang pengembangan **aplikasi real-time** dalam bidang kesehatan mental dan produktivitas.
* Chatbot sederhana berhasil dibuat sebagai **proof of concept** penggunaan model prediktif dalam interaksi pengguna.

---

✍️ *Capstone Project ini dibuat sebagai bagian dari pembelajaran pada program IBM SkillsBuild.*
