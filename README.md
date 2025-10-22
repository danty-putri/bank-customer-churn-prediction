# 🧠 Bank Customer Churn Prediction (IBM & Skilvul – Kampus Merdeka 6)

Proyek ini merupakan bagian dari program **Kampus Merdeka Batch 6: IBM & Skilvul Data Science Phase Challenge**.
Topik berikut untuk membangun model machine learning yang memprediksi kemungkinan nasabah bank berhenti menjadi pelanggan (churn).

---

## 📊 Problem Definition

Dalam industri perbankan, **retensi pelanggan (customer retention)** sangat penting untuk keberlanjutan bisnis.
Namun, banyak bank menghadapi masalah **churn**, yaitu ketika nasabah menutup akun atau berpindah ke bank lain.
Dengan menggunakan analisis data dan machine learning, proyek ini bertujuan untuk memprediksi kemungkinan churn berdasarkan perilaku dan data transaksi nasabah.

---

## 🎯 Tujuan Proyek

Mengembangkan model machine learning yang mampu:

1. Mengidentifikasi faktor-faktor utama yang mempengaruhi churn nasabah.
2. Memprediksi nasabah yang berpotensi churn.
3. Membantu bank melakukan tindakan preventif untuk mempertahankan pelanggan.

---

## 🧩 Dataset

* **Nama dataset:** `Churn_Modelling.csv`
* **Sumber:** [Kaggle – Banking Churn Analysis](https://www.kaggle.com/code/kdsharma/banking-churn-analysis-modeling/input)
* **Deskripsi:** Dataset ini berisi informasi tentang profil dan perilaku nasabah bank, termasuk:

  * `CreditScore`, `Geography`, `Gender`, `Age`, `Balance`, `EstimatedSalary`
  * Variabel target: `Exited` (1 = churn, 0 = tetap)

---

## ⚙️ Metode dan Model

Model yang digunakan dalam penelitian ini:

1. **Logistic Regression**
2. **Support Vector Machine (SVM)**
3. **Decision Tree Classifier**
4. **Random Forest Classifier**
5. **Gradient Boosting Classifier**

Masing-masing model dibandingkan berdasarkan akurasi dan metrik evaluasi lainnya seperti precision, recall, dan F1-score.

---

## 📈 Hasil dan Analisis

Model terbaik dipilih berdasarkan **akurasi tertinggi dan kemampuan generalisasi** terhadap data uji.
Proyek ini menunjukkan bagaimana pendekatan supervised learning dapat digunakan untuk memprediksi churn secara efektif.

---

## 💻 Cara Menjalankan Notebook

1. Clone repositori ini:

   ```bash
   git clone https://github.com/username/Bank-Customer-Churn-Prediction.git
   ```
2. Buka file notebook:

   ```bash
   Putri_Danty_Apriani_Build_an_ML_Model.ipynb
   ```
3. Jalankan notebook menggunakan **Jupyter Notebook** atau **Google Colab**.

---

## 🧠 Tools & Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Digunakan untuk analisis data, visualisasi, dan pembuatan model machine learning.

---

## 🧑‍💻 Author

**Putri Danty Apriani**
Universitas Sriwijaya
Kampus Merdeka – IBM & Skilvul Data Science Challenge
✨ “Turning data into actionable insights.” ✨

---

## 📂 Struktur Proyek

```
📦 Bank-Customer-Churn-Prediction
 ┣ 📜 Putri_Danty_Apriani_Build_an_ML_Model.ipynb
 ┣ 📜 README.md
 ┗ 📂 dataset/
    ┗ 📜 Churn_Modelling.csv
```
