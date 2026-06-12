# Analisis Pengaruh Metode Reduksi Dimensi terhadap Kinerja Support Vector Machine pada Klasifikasi Stadium Penyakit Alzheimer Berbasis Fitur Hibrida Citra MRI

## Nama Anggota

* Christine Aprilia Putri (24031554046)
* Nadia Kaila (24031554109)

## Dataset

Alzheimer's Disease Multiclass Images Dataset

## Tools

* Python
* OpenCV
* NumPy
* Pandas
* Scikit-Learn
* TensorFlow / Keras
* EfficientNetB3
* Matplotlib
* Seaborn

## Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis pengaruh metode reduksi dimensi terhadap kinerja algoritma Support Vector Machine (SVM) dalam klasifikasi stadium penyakit Alzheimer menggunakan citra Magnetic Resonance Imaging (MRI). Dataset yang digunakan terdiri dari empat kelas stadium Alzheimer, yaitu Mild Demented, Moderate Demented, Non-Demented, dan Very Mild Demented.

Penelitian menggunakan pendekatan ekstraksi fitur hibrida yang mengombinasikan fitur tekstur tradisional berupa Gray Level Co-occurrence Matrix (GLCM), Histogram of Oriented Gradients (HOG), dan Local Binary Pattern (LBP) dengan deep feature yang diekstraksi menggunakan EfficientNetB3. Kombinasi fitur tersebut menghasilkan representasi data berdimensi tinggi yang kemudian dievaluasi menggunakan beberapa skenario reduksi dimensi.

Metode reduksi dimensi yang dibandingkan dalam penelitian ini adalah Principal Component Analysis (PCA), Uniform Manifold Approximation and Projection (UMAP), serta skenario tanpa reduksi dimensi sebagai baseline. Selanjutnya, fitur hasil ekstraksi dan reduksi dimensi digunakan sebagai input bagi algoritma Support Vector Machine (SVM) untuk melakukan klasifikasi stadium penyakit Alzheimer.

## Tujuan Penelitian

* Mengklasifikasikan stadium penyakit Alzheimer menggunakan citra MRI.
* Mengevaluasi performa fitur tradisional dan deep feature dalam proses klasifikasi.
* Menganalisis pengaruh metode reduksi dimensi PCA dan UMAP terhadap kinerja SVM.
* Membandingkan performa model berdasarkan metrik Accuracy, Precision, Recall, dan F1-Score.
* Menentukan konfigurasi fitur dan reduksi dimensi yang paling efektif untuk klasifikasi stadium Alzheimer.

## Tahapan Penelitian

1. Exploratory Data Analysis (EDA)

   * Analisis distribusi kelas
   * Analisis intensitas piksel
   * Analisis dimensi citra
   * Visualisasi data

2. Preprocessing Citra

   * Resizing citra
   * Normalisasi piksel
   * Data splitting
   * Data augmentation

3. Ekstraksi Fitur

   * GLCM
   * HOG
   * LBP
   * EfficientNetB3

4. Pembentukan Fitur Hibrida

5. Reduksi Dimensi

   * PCA
   * UMAP
   * Tanpa reduksi dimensi

6. Klasifikasi

   * Support Vector Machine (SVM)

7. Evaluasi Model

   * Accuracy
   * Precision
   * Recall
   * F1-Score
   * Confusion Matrix

## Hasil Utama

Hasil penelitian menunjukkan bahwa fitur tradisional yang terdiri dari kombinasi GLCM, HOG, dan LBP memberikan performa yang lebih baik dibandingkan deep feature EfficientNetB3 pada dataset yang digunakan. Penerapan PCA mampu mempertahankan performa klasifikasi dengan jumlah fitur yang lebih sedikit, sedangkan UMAP menghasilkan penurunan performa pada kedua jenis fitur.

Secara keseluruhan, kombinasi fitur tradisional dan algoritma SVM memberikan hasil klasifikasi yang paling stabil untuk membedakan stadium penyakit Alzheimer berdasarkan citra MRI.

## Metrik Evaluasi

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Referensi Dataset

Alzheimer's Disease Multiclass Images Dataset (Equal and Augmented)

https://www.kaggle.com/datasets/aryansinghal10/alzheimers-multiclass-dataset-equal-and-augmented
