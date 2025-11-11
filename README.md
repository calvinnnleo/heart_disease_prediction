# Heart Disease Prediction with Machine Learning

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-1.0%2B-orange)](https://scikit-learn.org/stable/)

---

### 🧠 **Deskripsi Proyek**

Proyek ini bertujuan untuk **memprediksi risiko penyakit jantung** menggunakan data klinis pasien. Dengan memanfaatkan **algoritma Machine Learning**, model ini dapat membantu dalam tahap awal diagnosis dan skrining pasien.

Dataset: [Heart Disease UCI](https://archive.ics.uci.edu/ml/datasets/heart+disease)

---

### 📊 **Hasil & Metrik Model**

Model terbaik: **Random Forest** (tidak overfit, generalisasi baik)

| Model | Accuracy | F1-Score | AUC-ROC |
|-------|----------|----------|---------|
| Logistic Regression | 0.8049 | 0.8214 | 0.9253 |
| Random Forest | 0.9073 | 0.9140 | 0.9730 |

---

### 📈 **Visualisasi & Analisis**

Analisis disajikan dalam format Jupyter Notebook, mencakup:

- EDA (Exploratory Data Analysis)
- Visualisasi korelasi fitur
- Perbandingan performa model
- ROC Curve

➡️ **Lihat analisis dan visualisasi secara lengkap dalam link di bawah ini:**
[![nbviewer](https://img.shields.io/badge/view%20on-nbviewer-orange)](https://nbviewer.org/github/calvinnnleo/heart_disease_prediction/blob/main/Heart.ipynb)

💡 **Mengapa nbviewer?**  
GitHub tidak selalu menampilkan grafik dan output dari `.ipynb` dengan benar. Nbviewer menjamin semua visualisasi (grafik, tabel, output) ditampilkan utuh dan rapi.

---

### 🧰 **Teknologi & Library**

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `joblib`

---

### 📁 **File**

- `heart_disease_prediction.ipynb`: Notebook utama.
- `final_heart_disease_model.pkl`: Model terbaik yang telah disimpan.

---

### 🤝 **Kontribusi**

Kontribusi dan *pull request* selalu diterima.

---
