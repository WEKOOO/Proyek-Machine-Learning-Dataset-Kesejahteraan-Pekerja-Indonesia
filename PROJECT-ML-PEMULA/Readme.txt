# Proyek Machine Learning: Clustering dan Klasifikasi Menggunakan Dataset Kesejahteraan Pekerja Indonesia

## Deskripsi Proyek
Proyek ini bertujuan untuk melakukan analisis data menggunakan metode *clustering* dan *classification*.  
Proses *clustering* dilakukan terlebih dahulu untuk mengelompokkan data berdasarkan pola tertentu,  
kemudian hasil *clustering* digunakan sebagai dataset baru untuk proses klasifikasi.

## Struktur Proyek
Berikut adalah struktur proyek dan deskripsi setiap file yang digunakan:

1. **[Clustering] Submission Akhir BMLP_Weko_Abbror.ipynb**  
   - Notebook yang berisi proses *clustering* menggunakan algoritma K-Means.
   - Meliputi preprocessing data, eksplorasi, pemilihan jumlah cluster optimal, serta visualisasi hasil clustering.

2. **[Klasifikasi] Submission Akhir BMLP_Weko_Abbror.ipynb**  
   - Notebook yang berisi proses *classification* berdasarkan hasil *clustering*.
   - Meliputi pemisahan data, pemilihan model klasifikasi, evaluasi model, serta tuning hyperparameter.

3. **Dataset_clustering.csv**  
   - Dataset awal sebelum dilakukan proses *clustering*.
   - Digunakan dalam tahap eksplorasi dan pelatihan model *clustering*.

4. **Dataset_inisiasi.csv**  
   - Dataset hasil *clustering* yang telah diberi label cluster.
   - Digunakan sebagai input untuk model *classification*.

## Alur Proses
1. **Preprocessing Data**  
   - Menangani data yang hilang (*missing values*).  
   - Menghapus data duplikat dan mendeteksi outlier.  
   - Normalisasi atau standardisasi data numerik.  
   - Encoding fitur kategorikal.

2. **Clustering (Pengelompokan Data)**  
   - Menggunakan metode K-Means untuk mengelompokkan data.  
   - Menentukan jumlah cluster optimal menggunakan metode *Elbow* dan *Silhouette Score*.  
   - Memvisualisasikan hasil clustering.  
   - Melakukan inverse transform untuk mendapatkan kembali nilai asli fitur.

3. **Klasifikasi (Prediksi Cluster Baru)**  
   - Menggunakan dataset hasil *clustering* untuk membangun model klasifikasi.  
   - Membagi data menjadi *training set* dan *test set*.  
   - Melatih model dengan algoritma klasifikasi seperti Decision Tree, Random Forest, atau KNN.  
   - Mengevaluasi performa model menggunakan metrik *accuracy*, *F1-score*, dan *confusion matrix*.  
   - (Opsional) Melakukan tuning model menggunakan *GridSearchCV* atau *RandomizedSearchCV* untuk meningkatkan akurasi.

## Hasil dan Interpretasi
- Hasil *clustering* menunjukkan bahwa data dapat dikelompokkan menjadi beberapa kategori berdasarkan pola tertentu.  
- Model klasifikasi dibangun untuk dapat memprediksi kategori data baru berdasarkan hasil *clustering*.  
- Performa model dievaluasi dengan berbagai metrik untuk memastikan keakuratan prediksi.  

## Cara Menjalankan Proyek
1. Pastikan telah menginstal dependensi yang diperlukan (pandas, numpy, scikit-learn, seaborn, matplotlib, dll.).
2. Jalankan notebook *clustering* terlebih dahulu untuk menghasilkan dataset baru.
3. Jalankan notebook *klasifikasi* dengan menggunakan dataset hasil *clustering* sebagai input.
4. Analisis hasil klasifikasi dan interpretasikan hasilnya.

---

**Catatan:**  
- Jika ditemukan error dalam proses inverse transform, pastikan semua encoder dan scaler sudah disimpan dan digunakan kembali dengan benar.  
- Untuk meningkatkan performa model klasifikasi, eksperimen dengan berbagai algoritma dan tuning hyperparameter.  
