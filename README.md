
# Program Regresi Linier untuk Prediksi Penurunan Berat Badan Berdasarkan Waktu Latihan

## Deskripsi
Program ini menggunakan regresi linier untuk menganalisis hubungan antara waktu latihan harian dan penurunan berat badan. Dengan menggunakan pustaka Python seperti `pandas`, `numpy`, dan `scikit-learn`, program ini memproses data, membangun model prediktif, serta mengevaluasi kinerja model.

## Langkah-Langkah Program
1. **Impor Library**: Mengimpor pustaka yang diperlukan seperti `pandas`, `numpy`, `matplotlib`, dan `scikit-learn`.
2. **Memuat Dataset**: Membaca file CSV berisi data yang terdiri dari dua kolom - waktu latihan harian (X) dan penurunan berat badan (Y).
3. **Pra-Pemrosesan Data**:
   - Mengecek data kosong.
   - Melakukan pembersihan data dengan menghapus entri yang memiliki nilai kosong (jika ada).
4. **Membagi Dataset**:
   - Memisahkan data menjadi set pelatihan dan set pengujian.
   - Normalisasi data menggunakan `StandardScaler` agar setiap fitur memiliki skala yang seimbang.
5. **Membangun Model Regresi Linier**:
   - Melatih model dengan data pelatihan.
   - Menggunakan model untuk melakukan prediksi pada data pengujian.
6. **Evaluasi Model**:
   - Mengukur kinerja model dengan menghitung Mean Squared Error (MSE) dan nilai R² untuk mengetahui akurasi model dalam melakukan prediksi.
7. **Visualisasi**:
   - Menampilkan grafik regresi linier untuk menggambarkan hubungan antara waktu latihan dan penurunan berat badan.

## Cara Menjalankan Program
1. Pastikan pustaka yang dibutuhkan telah diinstal.
2. Jalankan setiap sel secara berurutan untuk mendapatkan hasil analisis dan visualisasi.

## Hasil Analisis
Program ini memberikan informasi mengenai akurasi model prediksi, dan visualisasi hasil prediksi dapat membantu dalam memahami pola hubungan antara variabel waktu latihan dan penurunan berat badan.

## Penulis
Indah Wulandari - 202231051

--- 

README ini menjelaskan tujuan, proses, dan hasil dari program regresi linier yang ada di notebook `regresi.ipynb`.
