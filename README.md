# 🧠 Brain Tumor Classification using KNN
Proyek ini bertujuan untuk melakukan klasifikasi tumor otak menggunakan metode K-Nearest Neighbors (KNN) berdasarkan fitur numerik hasil ekstraksi citra. Model akan memprediksi apakah suatu data termasuk tumor atau tidak tumor.
# 📊 Dataset
Dataset yang digunakan adalah **Brain Tumor Dataset** yang berisi fitur-fitur statistik dari citra, seperti:
- Mean
- Variance
- Entropy
- Homogeneity
- Contrast
- dan lain-lain

Target klasifikasi:
- 0 → No Tumor
- 1 → Tumor
# ⚙️ Teknologi yang Digunakan
- **Bahasa:** Python
- **Library Utama:**
    - **Scikit-Learn:** Untuk pemodelan KNN dan evaluasi model
    - **Pandas & Numpy:** Untuk manipulasi dan pengolahan data
    - **Matplotlib & Seaborn:** Untuk visualisasi data
    - **StandardScaler:** Untuk preprocessing (normalisasi fitur)
# 🚀 Alur Kerja Proyek
- **Data Loading:** Mengimpor dataset dari Google Drive menggunakan pandas
- **Exploratory Data Analysis (EDA):** Menganalisis data seperti distribusi kelas, statistik deskriptif, dan visualisasi fitur
- **Data Preprocessing:** Melakukan normalisasi fitur menggunakan StandardScaler agar semua fitur memiliki skala yang seragam
- **Splitting Data:** Membagi data menjadi **80% Training dan 20% Testing**
- **Tuning Parameter (K):** Mencoba beberapa nilai K (1–10) untuk menemukan nilai terbaik berdasarkan akurasi
- **Modeling:** Melatih model menggunakan **KNeighborsClassifier** dengan nilai K terbaik
- **Evaluation:** Mengevaluasi performa model menggunakan **Accuracy, Confusion Matrix, dan Classification Report (Precision, Recall, F1-score)**
# 📁 Struktur Project
- 2318023IraniLutfianiPutriKlasifikasiCitraTumorMetodeKNN.ipynb
- Brain Tumor.csv
- README.md
# Kontak
Dibuat oleh Irani Lutfiani Putri - https://www.linkedin.com/in/irani-lutfiani-8ba4b4331/?skipRedirect=true
