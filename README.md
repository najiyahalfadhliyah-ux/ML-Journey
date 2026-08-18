# ML-Journey

Roadmap belajar Machine Learning selama 12 minggu, mulai dari setup environment, pengolahan data, supervised learning, evaluasi model, hingga unsupervised learning.

## Roadmap Belajar

| Minggu Ke- | Topik Utama | Target Pemahaman | Output Proyek Mini |
| --- | --- | --- | --- |
| 1 | Setup Python Data Science | Menyiapkan Python, virtual environment, Jupyter Notebook atau VS Code, dapat juga menggunakan Google Colab atau Kaggle, Git, serta library `numpy`, `pandas`, `matplotlib`, `seaborn`, dan `scikit-learn`. Memahami struktur proyek ML. | Repository GitHub `ml-learning-journey` berisi notebook setup dan checklist environment |
| 2 | Python untuk Data dan NumPy | Menggunakan array NumPy, slicing, broadcasting, operasi vektor, serta memahami mengapa operasi array lebih efisien daripada loop manual. | Notebook analisis nilai mahasiswa menggunakan NumPy |
| 3 | Pandas Dasar | Membaca CSV, melihat struktur data, memilih kolom/baris, filtering, sorting, agregasi, `groupby`, dan ekspor hasil. | Analisis dataset transaksi sederhana, misalnya omzet per kategori dan pelanggan |
| 4 | Data Cleaning dan EDA | Menemukan missing value, duplikasi, tipe data salah, outlier sederhana, distribusi data, korelasi, dan visualisasi. | Laporan EDA satu dataset publik dalam notebook dengan minimal 5 insight |
| 5 | Fondasi Supervised ML | Memahami feature, target, training set, test set, baseline, `fit()`, `predict()`, dan mengapa data test tidak boleh dipakai saat training. | Prediksi harga rumah sederhana dengan Linear Regression |
| 6 | Evaluasi Regresi | Menggunakan MAE, MSE, RMSE, dan R². Membandingkan baseline dengan model dan membaca error prediksi. | Proyek prediksi harga rumah versi rapi dengan evaluasi dan analisis error |
| 7 | Klasifikasi Dasar | Memahami binary dan multiclass classification, probabilitas, threshold, Logistic Regression, serta confusion matrix. | Klasifikasi penumpang Titanic selamat atau tidak selamat |
| 8 | Evaluasi Klasifikasi | Menggunakan accuracy, precision, recall, F1-score, ROC-AUC, dan menangani class imbalance secara dasar. | Model deteksi spam atau fraud sederhana dengan laporan metrik |
| 9 | Decision Tree dan Random Forest | Memahami model berbasis aturan/pohon, feature importance, overfitting pada tree, dan keunggulan ensemble Random Forest. | Klasifikasi kualitas produk atau prediksi kelulusan dengan Random Forest |
| 10 | Preprocessing dan Pipeline | Encoding kategorikal, imputasi missing value, scaling, `ColumnTransformer`, `Pipeline`, dan pencegahan data leakage. | Pipeline produksi sederhana untuk dataset campuran numerik dan kategorikal |
| 11 | Validasi dan Tuning | Menggunakan cross-validation, `GridSearchCV` atau `RandomizedSearchCV`, memahami hyperparameter, dan membandingkan model secara adil. | Eksperimen tuning Random Forest atau Logistic Regression dengan tabel perbandingan |
| 12 | Unsupervised Learning dan Proyek Akhir | Memahami K-Means, clustering, PCA dasar, interpretasi cluster, dokumentasi proyek, dan penyajian hasil. | Segmentasi pelanggan atau clustering mahasiswa beserta rekomendasi berbasis data |

#### 1. Instalasi Python

Materi tentang instalasi Python dan pengecekan versi.

```bash
python --version
