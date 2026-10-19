# Tugas UTS Machine Learning

Repositori ini berisi penyelesaian Tugas Ujian Tengah Semester (UTS) mata kuliah Machine Learning. Proyek ini mencakup implementasi algoritma Machine Learning dari dasar (menggunakan NumPy) tanpa bantuan library pihak ketiga seperti Scikit-Learn untuk inti algoritmanya.

## 👩‍🎓 Identitas Mahasiswa
*   **Nama:** Maharani Putri Junaidi
*   **NIM:** 241011400308
*   **Kelas:** Reg CS (05TPLE005)

## Isi Repositori
*   `tugas_UTS.ipynb` : File Jupyter Notebook utama yang berisi kode dan analisis lengkap.
*   `Ads_Data.csv` : Dataset yang digunakan untuk kasus Regresi Linear (Prediksi Penjualan berdasarkan Biaya Iklan).
*   `Email_Data.csv` : Dataset yang digunakan untuk kasus Regresi Logistik (Klasifikasi Spam/Non-Spam).

## Ringkasan Pengerjaan
1.  **Bagian A (Regresi Linear):**
    *   Implementasi *train-test split* manual.
    *   Implementasi Regresi Linear menggunakan *Normal Equation*.
    *   Implementasi Regresi Linear menggunakan *Gradient Descent*.
    *   Evaluasi model menggunakan MAE, MSE, RMSE, dan R².
2.  **Bagian B (Regresi Logistik):**
    *   Implementasi algoritma Regresi Logistik dari awal (from scratch) menggunakan *Gradient Descent*.
    *   Evaluasi performa menggunakan *Confusion Matrix*, Accuracy, Precision, Recall, dan F1-Score.
    *   Analisis pengaruh perubahan *threshold* terhadap hasil klasifikasi.
3.  **Bagian C (Pemahaman Konsep):**
    *   Jawaban teoritis mengenai konsep dasar Machine Learning.
4.  **Bonus:**
    *   Perbandingan hasil model manual dengan hasil menggunakan library `scikit-learn`.

## Cara Menjalankan
1. Clone repositori ini atau download file zip-nya.
2. Buka file `tugas_UTS.ipynb` menggunakan Jupyter Notebook atau Google Colab.
3. Pastikan file dataset (`.csv`) berada di direktori yang sama dengan notebook.
4. Jalankan semua cell (Run All).
