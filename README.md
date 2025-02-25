# **Mini Project - Prediksi Kanker Payudara 🫀**  

## **📌 Deskripsi**  
Proyek ini bertujuan untuk menganalisis dan memprediksi jenis kanker payudara (**ganas atau jinak**) menggunakan dataset **Breast Cancer** dari `sklearn.datasets`. Dua model Machine Learning yang digunakan dalam prediksi ini:  

1. **Decision Tree Classifier** 🌳  
2. **Logistic Regression** 📊  

Dataset ini berisi berbagai fitur tumor seperti **ukuran, tekstur, simetri, dan karakteristik lainnya**. Tujuan utama proyek ini adalah membandingkan performa kedua model dalam melakukan klasifikasi kanker payudara.  

---

## **🔹 Dataset**  
- **Sumber:** `sklearn.datasets.load_breast_cancer()`  
- **Fitur:** 30 fitur numerik terkait karakteristik sel tumor  
- **Target:**  
  - `0` = **Kanker Ganas** 🚫  
  - `1` = **Kanker Jinak** ✅  

---

## **🔹 Metode yang Digunakan**  
✔ **Eksplorasi Data**: Menampilkan statistik dasar dan distribusi data  
✔ **Visualisasi Data**: Heatmap, pie chart, dan Confusion Matrix  
✔ **Preprocessing**: Pembagian data latih & uji (80:20)  
✔ **Modeling**:  
   - Decision Tree Classifier  
   - Logistic Regression  
✔ **Evaluasi Model**:  
   - Akurasi  
   - Classification Report (Precision, Recall, F1-score)  
   - Confusion Matrix  

---

## **🔹 Hasil Evaluasi**  
📊 Setelah melatih dan menguji model, diperoleh hasil sebagai berikut:  
- **Akurasi Decision Tree**: `91.23%`  
- **Akurasi Logistic Regression**: `95.61%`  

📈 *Hasil ini bisa berbeda tergantung parameter yang digunakan.*  

---

