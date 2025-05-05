# Dataset-Bunga-Naive-Bayes
Repositor ini merupakan project UTS mengenai ekperimen Dataset menggunakan Algoritma Naive Bayes
Berikut adalah README lengkap untuk file notebook `klasifikasi_naive_bayes_bunga.ipynb.txt` yang membahas implementasi klasifikasi menggunakan algoritma Naive Bayes pada dataset bunga iris:

---

# Klasifikasi Naive Bayes pada Dataset Iris

Notebook ini menjelaskan bagaimana menggunakan algoritma **Naive Bayes** untuk melakukan klasifikasi terhadap jenis bunga iris berdasarkan fitur ukurannya.

## Deskripsi Proyek

Proyek ini menggunakan dataset *Iris* yang terdiri dari 150 sampel bunga dengan tiga jenis (setosa, versicolor, virginica), masing-masing memiliki 4 fitur:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Tujuan dari proyek ini adalah membangun model klasifikasi menggunakan **Gaussian Naive Bayes** untuk memprediksi jenis bunga berdasarkan fitur-fitur tersebut.

## Struktur Notebook

1. **Import Library**
   Menggunakan pustaka:

   * `numpy`
   * `pandas`
   * `matplotlib.pyplot`
   * `seaborn`
   * `sklearn` (datasets, model\_selection, naive\_bayes, metrics)

2. **Load Dataset**
   Dataset iris dimuat dari pustaka `sklearn.datasets`.

3. **Eksplorasi dan Visualisasi Data**

   * Tabel deskriptif dataset
   * Pairplot untuk melihat sebaran data antar fitur dan jenis bunga

4. **Pra-pemrosesan Data**

   * Pemisahan fitur (X) dan label (y)
   * Pembagian data menjadi training dan testing set (80:20)

5. **Pelatihan Model Naive Bayes**

   * Menggunakan `GaussianNB` dari `sklearn.naive_bayes`
   * Melatih model dengan data training

6. **Evaluasi Model**

   * Prediksi pada data testing
   * Confusion matrix
   * Classification report (precision, recall, f1-score, accuracy)

## Cara Menjalankan

1. Pastikan Anda memiliki Python 3.x dan pustaka berikut:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

2. Jalankan notebook menggunakan Jupyter:

   ```bash
   jupyter notebook klasifikasi_naive_bayes_bunga.ipynb
   ```

## Hasil

Model Gaussian Naive Bayes menunjukkan hasil akurasi yang tinggi pada dataset ini, dengan nilai metrik evaluasi yang menunjukkan performa baik untuk semua kelas.

## Lisensi

Proyek ini menggunakan lisensi bebas. Dataset iris bersifat publik dan tersedia di pustaka `scikit-learn`.

---

Ingin saya bantu ubah ini ke dalam format markdown dan simpan sebagai file README.md?
